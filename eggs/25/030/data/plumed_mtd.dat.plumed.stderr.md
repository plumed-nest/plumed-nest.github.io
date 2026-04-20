**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_mtd.dat   
Download: [zipped raw stdout](plumed_mtd.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mtd.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:04166] *** Process received signal ***
[runnervmeorf1:04166] Signal: Aborted (6)
[runnervmeorf1:04166] Signal code:  (-6)
[runnervmeorf1:04166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a38a45330]
[runnervmeorf1:04166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a38a9eb2c]
[runnervmeorf1:04166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a38a4527e]
[runnervmeorf1:04166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a38a288ff]
[runnervmeorf1:04166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a38ea5ff5]
[runnervmeorf1:04166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a38ebb0da]
[runnervmeorf1:04166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a38ea5a55]
[runnervmeorf1:04166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a38ea5a6f]
[runnervmeorf1:04166] [ 8] plumed(+0x146dd)[0x5650ab10b6dd]
[runnervmeorf1:04166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a38a2a1ca]
[runnervmeorf1:04166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a38a2a28b]
[runnervmeorf1:04166] [11] plumed(+0x15365)[0x5650ab10c365]
[runnervmeorf1:04166] *** End of error message ***
</pre>
{% endraw %}
