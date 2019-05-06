# === Copyright
#
# Copyright (C) 2019  Atos Spain SA. All rights reserved.
#
# === License
#
# logstash/Dockerfile is free software: you can redistribute it and/or modify it under the 
# terms of the Apache License, Version 2.0 (the License);
# 
# http://www.apache.org/licenses/LICENSE-2.0
# 
# The software is provided "AS IS", without any warranty of any kind, express or implied,
# including but not limited to the warranties of merchantability, fitness for a particular
# purpose and noninfringement, in no event shall the authors or copyright holders be 
# liable for any claim, damages or other liability, whether in action of contract, tort or
# otherwise, arising from, out of or in connection with the software or the use or other
# dealings in the software.
# 
# See README file for the full disclaimer information and LICENSE file for full license 
# information in the project root.
# 
# == logstash/Dockerfile
#
# Logstash Dockerfile to configure logstash with ARI conf
# 
# === Authors
#
# Author	Carlos Cavero
#			Atos Research and Innovation, Atos SPAIN SA
# 

FROM logstash:6.4.2

COPY logstash.conf /config-dir/

CMD ["logstash", "-f", "/config-dir/logstash.conf"]