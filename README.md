#Create an image on Digital Ocean

    $ git clone https://github.com/toshimaru/packer-digitalocean-sample
    $ cd packer-digitalocean-sample

Add your own `client_id` and `api_key` in `Packer.json`.

    $ packer build Packer.json

#See also
* <http://www.packer.io/docs>
* <http://www.packer.io/docs/builders/digitalocean.html>
* <https://www.digitalocean.com/community/articles/how-to-install-and-get-started-with-packer-on-an-ubuntu-12-04-vps>
* [packerを使ってDigital Ocean上にイメージを作成する](http://blog.toshimaru.net/digitalocean-image-with-packer/)
