**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmgx7h7:11263] *** Process received signal ***
[runnervmgx7h7:11263] Signal: Aborted (6)
[runnervmgx7h7:11263] Signal code:  (-6)
[runnervmgx7h7:11263] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b33645330]
[runnervmgx7h7:11263] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b3369ec0c]
[runnervmgx7h7:11263] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b3364527e]
[runnervmgx7h7:11263] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b336288ff]
[runnervmgx7h7:11263] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b33aa5ff5]
[runnervmgx7h7:11263] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b33abb0da]
[runnervmgx7h7:11263] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b33aa5a55]
[runnervmgx7h7:11263] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b33aa5a6f]
[runnervmgx7h7:11263] [ 8] plumed_master(+0x146dd)[0x55e52ff2c6dd]
[runnervmgx7h7:11263] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b3362a1ca]
[runnervmgx7h7:11263] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b3362a28b]
[runnervmgx7h7:11263] [11] plumed_master(+0x15365)[0x55e52ff2d365]
[runnervmgx7h7:11263] *** End of error message ***
</pre>
{% endraw %}
