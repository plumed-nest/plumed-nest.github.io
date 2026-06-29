**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmmklqx:05305] *** Process received signal ***
[runnervmmklqx:05305] Signal: Aborted (6)
[runnervmmklqx:05305] Signal code:  (-6)
[runnervmmklqx:05305] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad62445330]
[runnervmmklqx:05305] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad6249eb2c]
[runnervmmklqx:05305] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad6244527e]
[runnervmmklqx:05305] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad624288ff]
[runnervmmklqx:05305] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad628a5ff5]
[runnervmmklqx:05305] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad628bb0da]
[runnervmmklqx:05305] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad628a5a55]
[runnervmmklqx:05305] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad628a5a6f]
[runnervmmklqx:05305] [ 8] plumed(+0x146dd)[0x558821e916dd]
[runnervmmklqx:05305] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad6242a1ca]
[runnervmmklqx:05305] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad6242a28b]
[runnervmmklqx:05305] [11] plumed(+0x15365)[0x558821e92365]
[runnervmmklqx:05305] *** End of error message ***
</pre>
{% endraw %}
