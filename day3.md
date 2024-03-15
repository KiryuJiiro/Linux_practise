###  cp: 
    copy command 
    syntax: [file_path] [new_destination] (copies file)
    cp -R [current_directory] [new_directory](copies folder)
	eg cp new.txt \Desktop\NewFolder
###  mv: 
    move file
    mv [file_name] [new_destination](moves file to new_destination]
    eg:mv new.txt newfolder
    rename and move:mv new.txt newfolder/test.txt
###  file:
    gives information about file
    syntax:file [file_name]
    file -k -i [file_name]
###  zip/unzip:
    compresses file and extracts file
    syntax:zip [zip_name] [file_name]
    syntax:unzip [zip_file]
    eg:zip new.zip new.txt
    unzip new.zip
###  ==ping==:
    checks if network or any system is up
    syntax: ping (network troubleshoot, command, host, are reacheable or not)
    eg: ping aniwave.com
###  ==tee==:
	makes a file out of texts in terminal
	syntax:tee [file_name]
	ping google.com | tee new.txt  
###  df:
    shows disk usage
    syntax: df
    df -k(in MB)
    df -m(in KB)
    df -T(shows type)

