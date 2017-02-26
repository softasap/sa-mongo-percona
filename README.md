sa-mongo-percona
================

[![Build Status](https://travis-ci.org/softasap/sa-mongo-percona.svg?branch=master)](https://travis-ci.org/softasap/sa-mongo-percona)


Percona Server for MongoDB is a free, enhanced, fully compatible, open source, drop-in replacement for the MongoDB® Community Edition that includes enterprise-grade features and functionality. 

Role to install Percona MongoDB 3.4 compatible alternative to Mongo DB Community edition  on ubuntu based box.

Version is controlled by  mongo_version parameter.

mongo_version: "3.4"  #  For compability with sa-mongo, only 3.4 supported so far


Example:

Simple

```YAML


     - {
         role: "sa-mongo-percona"
       }

```

Advanced:

```YAML


     - {
         role: "sa-mongo-percona",
         mongo_version: "3.4"
       }

```




Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-mongo-percona role using the command


`
   ansible galaxy install softasap.sa-mongo-percona
`

the role will be available in the folder library\softasap.mongo.
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.mongo-percona"
       }

```


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)


