# my-docker-amp

Gyökérbe tedd a **/htdocs** mappát, itt lesznek a weboldalaid. Ezt a mappát a docker beállításaiban engedélyezd megosztottnak a dockerrel. Ezen belül hozz létre pl egy **.server** mappát. Itt lesznek a vhost filejaid, illetve hozz létre egy könyvtárat ennek a repositorynak. Chekcout és ```docker-compose up``` ! :)


Create a **/htdocs** in the root, there will be your websites. In the docker settings add this folder at the file sharing section. Inside this folder create a **.server** folder. Put your vhost (apache virtualhost) files, and chekout this repo into the **.server** dolder. Than in terminal (cmd) run ```docker-compose up```! :)
