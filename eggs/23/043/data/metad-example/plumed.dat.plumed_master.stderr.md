**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmxyh4eaekms:07864] *** Process received signal ***
[pkrvmxyh4eaekms:07864] Signal: Aborted (6)
[pkrvmxyh4eaekms:07864] Signal code:  (-6)
[pkrvmxyh4eaekms:07864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2955445330]
[pkrvmxyh4eaekms:07864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f295549eb2c]
[pkrvmxyh4eaekms:07864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f295544527e]
[pkrvmxyh4eaekms:07864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29554288ff]
[pkrvmxyh4eaekms:07864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29558a5ff5]
[pkrvmxyh4eaekms:07864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29558bb0da]
[pkrvmxyh4eaekms:07864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29558a5a55]
[pkrvmxyh4eaekms:07864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29558a5a6f]
[pkrvmxyh4eaekms:07864] [ 8] plumed_master(+0x146dd)[0x562ecf3f46dd]
[pkrvmxyh4eaekms:07864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f295542a1ca]
[pkrvmxyh4eaekms:07864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f295542a28b]
[pkrvmxyh4eaekms:07864] [11] plumed_master(+0x15365)[0x562ecf3f5365]
[pkrvmxyh4eaekms:07864] *** End of error message ***
</pre>
{% endraw %}
