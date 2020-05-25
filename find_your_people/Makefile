all: 
	jekyll build

clean:
	jekyll clean

install: all
	rsync -av --progress _site/ root@wp-shack.tedstechshack.com:/var/www/wildernessguides.org/blog/
