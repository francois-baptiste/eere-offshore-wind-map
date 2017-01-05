## Client Application

This app is hosted on github.io and used on energy.gov at: http://energy.gov/eere/wind/maps/offshore-wind-funding

Deployment of this folder and application is done via simple git subtree deployment. (https://gist.github.com/cobyism/4730490)

Example:

git clone git@github.com:NREL/eere-offshore-wind-map.git

cd eere-offshore-wind-map

git checkout -b gh-pages remotes/origin/gh-pages

git checkout mastergit subtree push --prefix client origin gh-pages

git push using:  origin gh-pages

Counting objects: 3, done.

Delta compression using up to 4 threads.

Compressing objects: 100% (1/1), done.

Writing objects: 100% (3/3), 303 bytes | 0 bytes/s, done.

Total 3 (delta 2), reused 2 (delta 2)

remote: Resolving deltas: 100% (2/2), completed with 2 local objects.

To github.com:NREL/eere-offshore-wind-map.git   

    b470990..372d8b1  372d8b1983b50d20d93d7a628c068774b0c3a8b2 -> gh-pages
