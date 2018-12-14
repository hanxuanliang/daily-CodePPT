title: Backup and Recovery + Social Networking
speaker: hanxuanliang
url: https://github.com/ksky521/nodeppt
transition: cards
files: /js/demo.js,/css/demo.css

[slide]

# Backup and Recovery + Social Networking
## Speaker：Group 6

[slide]

# Traditional backup 
----
* Focus on <span class="blue">large data</span> volume backup {:&.rollIn}
* Back up the <span class="red">entire IT system</span>
* Establish <span class="green">separate data disaster</span> preparedness center
* Requirements for <span class="black">customizing complex backup plans</span>
* Restore <span class="yellow">slower</span>

[slide]

## Cloud backup
----
* Reduce the cost {:&.bounceIn}
* Safe and efficient system
* Anytime anywhere access
* Cloud database version upgrade is very cool

[slide]
[note]
## Note
1. A typical enterprise backup application must have 100% locally stored data and can only copy copies of that data to the cloud. In other words, they don't have new features, and they can move back up to the cloud. These solutions use cloud computing as a mirror image of their internally deployed storage.
> 典型的企业备份应用程序必须拥有100%的本地存储的数据，并且只能将该数据的副本复制到云端。换句话说，他们没有新的功能，他们可以将原有的数据备份移动到云端。这些解决方案使用云计算作为其内部部署存储的镜像。

2. Will allow older data backups to be archived to cloud storage, thereby minimizing the cost of backup storage for local internal deployment. Copies of the data deployed on the local side need to contain data from the last 90 days or so, and can provide a 99% recovery rate over a certain period of time. Backup solutions that aim to archive to the cloud should be able to reduce locally deployed storage data eightfold or more.
> 将允许将较旧的数据备份存档到云存储，从而将本地内部部署的备份存储成本降至最低。本地侧部署的数据副本需要包含最近90天左右的数据，并且可以在一定的时间范围内提供99%的恢复率。旨在存档到云端的备份解决方案应该能够将本地部署的存储数据减少8倍或更多。
[/note]

## The solution
----
* Internal deployment {:&.rollIn}
* Older data backup 
* Mirroring and archiving

[slide]

## Depending on
{:&.flexbox.vleft}
----
* The amount of data that needs to be protected {:&.zoomIn}
* Available network bandwidth
* Data change rate
* ...

[slide]

## Hybrid cloud backup
----
* Safe and reliable {:&.rollIn} <br />
  > End-to-end data encryption validation mechanism <br />
* High-speed and efficient
  > Source side deduplication <br />
  > Data compression
* extensible <br />
  > Unlimited expansion of backup libraries <br />
* Universal coverage <br />
  > Full support for directories under mainstream operating systems

[slide style="background-image:url('/img/paolu.gif')"] [magic data-transition="cover-circle"]
# <span class="red">Recovery?</span>

[slide]
## <span class="label label-primary">The backup is ready. Isn't it easy to Recovery</span>
---- 
* silent {:&.fadeIn} <br />
> Data recovery should not affect the user's experience
![mysqlbackup](/img/mysqlbackup.jpg)
* speed <br />
> Can not affect the use of users for a long time


[slide data-transition="vertical3d" style="background-image:url('/img/wikisocial.png')"]
## <span class="black">Social Networking</span>
> Social network is a network structure composed of many nodes and their relationships. A node is usually an individual or organization (also known as a community). Social networks represent relationships that connect people or organizations from casual acquaintances to close-knit family relationships. Social networks depend on one or more relationships, such as values, ideals, ideas, interests, friendships, kinship, common aversions, conflicts, or trade. The resulting network structure is often very complex. <small>WIKI</small> {:&.pull-right}

[slide]
[note]
# Six Degrees of Separation
> The idea that any two people in the world who don't know each other need very few middlemen to make a connection <br />
> 认为世界上任何互不相识的两人，只需要很少的中间人就能够建立起联系
[/note]
## The environment 
![社交网络应用基础](/img/social.png)

[slide]
## What do we need clouds for?
----
* Search system {:&.rollIn}
* Recommendation system
* User-generated multimedia data
* User behavior analysis <br />
  > Based on cloud data warehouse
  <br />
  <br />
  ![大数据](/img/bigdata.png)

[slide]

# Overall
# <span class="green">Data</span> is what matters


[slide data-transition="vertical3d"]
# Thank for listening

Github：https://github.com/hanxuanliang/dailyCodePPT



