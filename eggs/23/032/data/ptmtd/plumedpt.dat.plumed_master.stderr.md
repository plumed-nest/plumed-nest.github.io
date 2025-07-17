**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmq0rgcvqdmg:07541] *** Process received signal ***
[pkrvmq0rgcvqdmg:07541] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07541] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07541] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde8a645330]
[pkrvmq0rgcvqdmg:07541] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde8a69eb2c]
[pkrvmq0rgcvqdmg:07541] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde8a64527e]
[pkrvmq0rgcvqdmg:07541] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde8a6288ff]
[pkrvmq0rgcvqdmg:07541] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde8aaa5ff5]
[pkrvmq0rgcvqdmg:07541] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde8aabb0da]
[pkrvmq0rgcvqdmg:07541] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde8aaa5a55]
[pkrvmq0rgcvqdmg:07541] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde8aaa5a6f]
[pkrvmq0rgcvqdmg:07541] [ 8] plumed_master(+0x146dd)[0x5630c7eae6dd]
[pkrvmq0rgcvqdmg:07541] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde8a62a1ca]
[pkrvmq0rgcvqdmg:07541] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde8a62a28b]
[pkrvmq0rgcvqdmg:07541] [11] plumed_master(+0x15365)[0x5630c7eaf365]
[pkrvmq0rgcvqdmg:07541] *** End of error message ***
</pre>
{% endraw %}
