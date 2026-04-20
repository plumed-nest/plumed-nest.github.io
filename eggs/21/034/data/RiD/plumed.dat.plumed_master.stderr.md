**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmeorf1:08511] *** Process received signal ***
[runnervmeorf1:08511] Signal: Aborted (6)
[runnervmeorf1:08511] Signal code:  (-6)
[runnervmeorf1:08511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6064645330]
[runnervmeorf1:08511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f606469eb2c]
[runnervmeorf1:08511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f606464527e]
[runnervmeorf1:08511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60646288ff]
[runnervmeorf1:08511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6064aa5ff5]
[runnervmeorf1:08511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6064abb0da]
[runnervmeorf1:08511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6064aa5a55]
[runnervmeorf1:08511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6064aa5a6f]
[runnervmeorf1:08511] [ 8] plumed_master(+0x146dd)[0x55b302a196dd]
[runnervmeorf1:08511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f606462a1ca]
[runnervmeorf1:08511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f606462a28b]
[runnervmeorf1:08511] [11] plumed_master(+0x15365)[0x55b302a1a365]
[runnervmeorf1:08511] *** End of error message ***
</pre>
{% endraw %}
