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
[runnervmkj6or:11379] *** Process received signal ***
[runnervmkj6or:11379] Signal: Aborted (6)
[runnervmkj6or:11379] Signal code:  (-6)
[runnervmkj6or:11379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2f9a45330]
[runnervmkj6or:11379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2f9a9eb2c]
[runnervmkj6or:11379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2f9a4527e]
[runnervmkj6or:11379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2f9a288ff]
[runnervmkj6or:11379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2f9ea5ff5]
[runnervmkj6or:11379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2f9ebb0da]
[runnervmkj6or:11379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2f9ea5a55]
[runnervmkj6or:11379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2f9ea5a6f]
[runnervmkj6or:11379] [ 8] plumed_master(+0x146dd)[0x55b48fa516dd]
[runnervmkj6or:11379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2f9a2a1ca]
[runnervmkj6or:11379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2f9a2a28b]
[runnervmkj6or:11379] [11] plumed_master(+0x15365)[0x55b48fa52365]
[runnervmkj6or:11379] *** End of error message ***
</pre>
{% endraw %}
