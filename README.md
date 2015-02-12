# Turtlebot Map

A place to collect location information about TurtleBot users.

Required Information
--------------------

If it's a new distributor,

* Name
* Web URL
* Latitude/Longitude (use google maps)

Other Updates
-------------

We keep a kobuki/turtlebot combined map up to date as well. If you want that updated as well, be sure to mark them on the [kobuki distributors map](https://github.com/yujinrobot/kobuki_distributors) as well.

How to Update
-------------

I find it easiest just to make pull requests from [direct edits](https://github.com/turtlebot/map/edit/master/Distributors.geojson).

For pretty editing -> [use this link](http://geojson.io/#id=github:turtlebot/map/blob/master/Distributors.geojson). The github interaction seems rather awkward though. 

Embedding the Map in a Web Page
-------------------------------

Use this snippet:

```
<script src="https://embed.github.com/view/geojson/turtlebot/map/master/Distributors.geojson"></script>
```
