**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmq0rgcvqdmg:07525] *** Process received signal ***
[pkrvmq0rgcvqdmg:07525] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07525] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07525] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83fce45330]
[pkrvmq0rgcvqdmg:07525] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83fce9eb2c]
[pkrvmq0rgcvqdmg:07525] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83fce4527e]
[pkrvmq0rgcvqdmg:07525] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83fce288ff]
[pkrvmq0rgcvqdmg:07525] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83fd2a5ff5]
[pkrvmq0rgcvqdmg:07525] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83fd2bb0da]
[pkrvmq0rgcvqdmg:07525] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83fd2a5a55]
[pkrvmq0rgcvqdmg:07525] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83fd2a5a6f]
[pkrvmq0rgcvqdmg:07525] [ 8] plumed(+0x146dd)[0x55a3f07af6dd]
[pkrvmq0rgcvqdmg:07525] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83fce2a1ca]
[pkrvmq0rgcvqdmg:07525] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83fce2a28b]
[pkrvmq0rgcvqdmg:07525] [11] plumed(+0x15365)[0x55a3f07b0365]
[pkrvmq0rgcvqdmg:07525] *** End of error message ***
</pre>
{% endraw %}
