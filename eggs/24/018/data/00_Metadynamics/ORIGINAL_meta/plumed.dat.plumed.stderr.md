**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:05703] *** Process received signal ***
[runnervm76f27:05703] Signal: Aborted (6)
[runnervm76f27:05703] Signal code:  (-6)
[runnervm76f27:05703] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a35445330]
[runnervm76f27:05703] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a3549ec0c]
[runnervm76f27:05703] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a3544527e]
[runnervm76f27:05703] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a354288ff]
[runnervm76f27:05703] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a358a5ff5]
[runnervm76f27:05703] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a358bb0da]
[runnervm76f27:05703] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a358a5a55]
[runnervm76f27:05703] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a358a5a6f]
[runnervm76f27:05703] [ 8] plumed(+0x146dd)[0x5625999b36dd]
[runnervm76f27:05703] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a3542a1ca]
[runnervm76f27:05703] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a3542a28b]
[runnervm76f27:05703] [11] plumed(+0x15365)[0x5625999b4365]
[runnervm76f27:05703] *** End of error message ***
</pre>
{% endraw %}
