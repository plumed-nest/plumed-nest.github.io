**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmf6wy0o8zjz:63390] *** Process received signal ***
[pkrvmf6wy0o8zjz:63390] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63390] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63390] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f89dbc45330]
[pkrvmf6wy0o8zjz:63390] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f89dbc9eb2c]
[pkrvmf6wy0o8zjz:63390] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f89dbc4527e]
[pkrvmf6wy0o8zjz:63390] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89dbc288ff]
[pkrvmf6wy0o8zjz:63390] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f89dc0a5ff5]
[pkrvmf6wy0o8zjz:63390] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f89dc0bb0da]
[pkrvmf6wy0o8zjz:63390] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f89dc0a5a55]
[pkrvmf6wy0o8zjz:63390] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f89dc0a5a6f]
[pkrvmf6wy0o8zjz:63390] [ 8] plumed_master(+0x146dd)[0x56380cb766dd]
[pkrvmf6wy0o8zjz:63390] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f89dbc2a1ca]
[pkrvmf6wy0o8zjz:63390] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f89dbc2a28b]
[pkrvmf6wy0o8zjz:63390] [11] plumed_master(+0x15365)[0x56380cb77365]
[pkrvmf6wy0o8zjz:63390] *** End of error message ***
</pre>
{% endraw %}
