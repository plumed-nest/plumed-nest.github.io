**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervm0kj6c:09695] *** Process received signal ***
[runnervm0kj6c:09695] Signal: Aborted (6)
[runnervm0kj6c:09695] Signal code:  (-6)
[runnervm0kj6c:09695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f360b645330]
[runnervm0kj6c:09695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f360b69eb2c]
[runnervm0kj6c:09695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f360b64527e]
[runnervm0kj6c:09695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f360b6288ff]
[runnervm0kj6c:09695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f360baa5ff5]
[runnervm0kj6c:09695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f360babb0da]
[runnervm0kj6c:09695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f360baa5a55]
[runnervm0kj6c:09695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f360baa5a6f]
[runnervm0kj6c:09695] [ 8] plumed_master(+0x146dd)[0x55cdc8fdf6dd]
[runnervm0kj6c:09695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f360b62a1ca]
[runnervm0kj6c:09695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f360b62a28b]
[runnervm0kj6c:09695] [11] plumed_master(+0x15365)[0x55cdc8fe0365]
[runnervm0kj6c:09695] *** End of error message ***
</pre>
{% endraw %}
