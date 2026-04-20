**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmeorf1:09712] *** Process received signal ***
[runnervmeorf1:09712] Signal: Aborted (6)
[runnervmeorf1:09712] Signal code:  (-6)
[runnervmeorf1:09712] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f423ba45330]
[runnervmeorf1:09712] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f423ba9eb2c]
[runnervmeorf1:09712] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f423ba4527e]
[runnervmeorf1:09712] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f423ba288ff]
[runnervmeorf1:09712] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f423bea5ff5]
[runnervmeorf1:09712] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f423bebb0da]
[runnervmeorf1:09712] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f423bea5a55]
[runnervmeorf1:09712] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f423bea5a6f]
[runnervmeorf1:09712] [ 8] plumed_master(+0x146dd)[0x5558b20946dd]
[runnervmeorf1:09712] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f423ba2a1ca]
[runnervmeorf1:09712] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f423ba2a28b]
[runnervmeorf1:09712] [11] plumed_master(+0x15365)[0x5558b2095365]
[runnervmeorf1:09712] *** End of error message ***
</pre>
{% endraw %}
