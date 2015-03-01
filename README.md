# vimeo_video_download
A Golang app for downloading http://storage.googleapis.com/vimeo-test/work-at-vimeo.mp4 with a variable number of download threads to download the file in range chuncks.

  Clone the repo.

    $ git clone https://github.com/desmondmcnamee/vimeo_video_download.git

  Run the app and pass the number of download threads you'd like to create.

    $ go run vimeo.go <# of DL threads>
