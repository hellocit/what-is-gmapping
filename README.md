# what-is-gmapping
gmappingとはSLAMのためのアルゴリズムをROSで使用できるようにしたものである．
# 目的
ROSパッケージのslam_gmappingを説明すること
# ソースコード
1.のslam_gmappingを使用する．
# このREADMEの構成
slam_gmappingのディレクトリ構成について説明し，それぞれのファイルについて説明する．
# ディレクトリの構成
1.をワーキングディレクトリとしたときの写真を以下に示す．
![top-page](https://github.com/hellocit/what-is-gmapping/blob/image/a.png)

* README.md 
    * ROSパッケージを使用する際に読んでおくべきドキュメント
* gmapping
    * SLAMの本体
* slam_gmapping
    * CHANGELOG.rst
        * ROSのbloomという機能を使う際に必要なファイル
    * CMakeLists.txt
        * 使用するライブラリを記述するファイル
    * package.xml
        * catkin_create_pkgするときに作成されるファイルである．このファイルはパッケージのせつめいや作った人の紹介，ライセンスなどの様々な情報を記述するファイルである．

# what-is-gmapping/slam_gmapping/gmapping



# 完走
なぜかgmappingのリポジトリが二つある．References参照のこと
# References
1. https://github.com/ros-perception/slam_gmapping
1. https://github.com/ros-perception/openslam_gmapping
1. https://qiita.com/shrimp-f/items/63f38c45ee44777b02a0



# Appendix
* https://cakecatz.hatenadiary.com/entry/2015/02/10/214942
    * branchを変えてgithubに画像を掲載する方法