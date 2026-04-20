**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06195] *** Process received signal ***
[runnervmeorf1:06195] Signal: Aborted (6)
[runnervmeorf1:06195] Signal code:  (-6)
[runnervmeorf1:06195] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdb5845330]
[runnervmeorf1:06195] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdb589eb2c]
[runnervmeorf1:06195] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdb584527e]
[runnervmeorf1:06195] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdb58288ff]
[runnervmeorf1:06195] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdb5ca5ff5]
[runnervmeorf1:06195] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdb5cbb0da]
[runnervmeorf1:06195] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdb5ca5a55]
[runnervmeorf1:06195] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdb5ca5a6f]
[runnervmeorf1:06195] [ 8] plumed(+0x146dd)[0x556946cfd6dd]
[runnervmeorf1:06195] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdb582a1ca]
[runnervmeorf1:06195] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdb582a28b]
[runnervmeorf1:06195] [11] plumed(+0x15365)[0x556946cfe365]
[runnervmeorf1:06195] *** End of error message ***
</pre>
{% endraw %}
