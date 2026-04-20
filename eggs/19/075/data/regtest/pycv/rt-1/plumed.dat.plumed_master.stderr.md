**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:09556] *** Process received signal ***
[runnervmeorf1:09556] Signal: Aborted (6)
[runnervmeorf1:09556] Signal code:  (-6)
[runnervmeorf1:09556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa23b245330]
[runnervmeorf1:09556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa23b29eb2c]
[runnervmeorf1:09556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa23b24527e]
[runnervmeorf1:09556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa23b2288ff]
[runnervmeorf1:09556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa23b6a5ff5]
[runnervmeorf1:09556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa23b6bb0da]
[runnervmeorf1:09556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa23b6a5a55]
[runnervmeorf1:09556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa23b6a5a6f]
[runnervmeorf1:09556] [ 8] plumed_master(+0x146dd)[0x5585ec4496dd]
[runnervmeorf1:09556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa23b22a1ca]
[runnervmeorf1:09556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa23b22a28b]
[runnervmeorf1:09556] [11] plumed_master(+0x15365)[0x5585ec44a365]
[runnervmeorf1:09556] *** End of error message ***
</pre>
{% endraw %}
