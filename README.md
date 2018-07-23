# HuRiMa
## Hubrix Rights Manager
![License](https://img.shields.io/badge/license-CONFIDENTIAL-orange.svg)
![Node](https://img.shields.io/badge/node-%3E%3D%208.9.4%20%3C%209.0-yellow.svg)
![Build Status](https://circleci.com/bb/hurima/hurima-core.svg?style=shield&circle-token=3c66405ab8ddb83a3535f57d3dce7648a68bf24d)
[![Twitter Follow](https://img.shields.io/twitter/follow/hubrixco.svg?style=social&logo=twitter&label=Follow)](https://twitter.com/intent/follow?screen_name=hubrixco)

A RESTful API written in node.js to provide function-based access control (FBAC) to new applications as well as a number of existing ones.

We hope to introduce some innovations we believe will be a significant improvement over

* Role-based Access Control (RBAC)
* Attribute-based Access Control (ABAC)

for some use cases.

Our initial focus areas:
 - Improving granularity and audit capabilites of rights/permissions management in open-source CMS and blog platforms
 - Building an API that allows rights and permissions to be managed across several domains / applications / platforms etc.
 
 More information at https://www.hubrix.co/hurima/
 ## DB schema

 SQL source to initialize the MySQL database is in the `schema` folder.

The Hurima database schema is just a `.sql` file. In time we'll get smarter about version-managing DB schema (so we can better deploy them).

Will be pasting the Schema notes here in near future. Meanwhile, the latest notes are in GDrive in: https://docs.google.com/document/d/1_1m-loQjivZgSHa3MWl2bnJkUg6R9rM1dJrx92PK61E/edit?usp=sharing

 ## Hey, why is there no source code here?
 
31 Oct 2017 update: **Hurima 1.0 is in development now.** Our initial release will be followed by a **closed Beta test** (limited to 100 users). You can sign up for the Beta here: https://www.hubrix.co/hurima-beta-signup/

27 Nov 2017 update: **We have 64 open slots remaining for the Hurima Beta.** We're presently aiming for a start date of 03 April, 2018 for the Beta but that may change depending on development progress. Please visit our Web site (link above) to sign up.

 Hurima _will_ be an open source project, but our policy is to only post working, tested code on GitHub. Thanks for understanding.

