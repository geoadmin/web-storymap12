storymap12
==========

BAFU Lärm: Massnahmen gegen Lärm

http://storymaps.geo.admin.ch/storymaps/storymap12/

1/ Install 

    cd /var/www/vhosts/web-storymap12/private 

    git clone git@github.com:geoadmin/web-storymap12.git storymap
    
    cd storymap
    
    sudo apache2ctl graceful

2/ Deploy

    cd /var/www/vhosts/web-storymap12/private/storymap

    sudo -u deploy deploy -r deploy/deploy.cfg int   # or prod
