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
[fv-az585-767:04588] *** Process received signal ***
[fv-az585-767:04588] Signal: Aborted (6)
[fv-az585-767:04588] Signal code:  (-6)
[fv-az585-767:04588] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3fd6242520]
[fv-az585-767:04588] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3fd62969fc]
[fv-az585-767:04588] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3fd6242476]
[fv-az585-767:04588] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3fd62287f3]
[fv-az585-767:04588] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3fd66a2b9e]
[fv-az585-767:04588] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3fd66ae20c]
[fv-az585-767:04588] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3fd66ae277]
[fv-az585-767:04588] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3fd66ae52b]
[fv-az585-767:04588] [ 8] plumed(+0x14254)[0x55b761aa0254]
[fv-az585-767:04588] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3fd6229d90]
[fv-az585-767:04588] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3fd6229e40]
[fv-az585-767:04588] [11] plumed(+0x14eb5)[0x55b761aa0eb5]
[fv-az585-767:04588] *** End of error message ***
</pre>
{% endraw %}
