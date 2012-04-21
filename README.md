# mobile app boileplate

 * phonegap 1.6
 * jquery mobile 1.1

## update project

pick up an id

	android list targets

update project

	android update project -p . -t "id here"

## build and install app

plug in you phone, enable debug mode `settings > applications > development`, then

	sudo adb start-server
	ant install

## allow ajax request in google-chrome

	google-chrome --allow-file-access-from-files  --disable-web-security
