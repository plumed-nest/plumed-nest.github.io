**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmxyh4eaekms:07848] *** Process received signal ***
[pkrvmxyh4eaekms:07848] Signal: Aborted (6)
[pkrvmxyh4eaekms:07848] Signal code:  (-6)
[pkrvmxyh4eaekms:07848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f139de45330]
[pkrvmxyh4eaekms:07848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f139de9eb2c]
[pkrvmxyh4eaekms:07848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f139de4527e]
[pkrvmxyh4eaekms:07848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f139de288ff]
[pkrvmxyh4eaekms:07848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f139e2a5ff5]
[pkrvmxyh4eaekms:07848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f139e2bb0da]
[pkrvmxyh4eaekms:07848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f139e2a5a55]
[pkrvmxyh4eaekms:07848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f139e2a5a6f]
[pkrvmxyh4eaekms:07848] [ 8] plumed(+0x146dd)[0x55e16137c6dd]
[pkrvmxyh4eaekms:07848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f139de2a1ca]
[pkrvmxyh4eaekms:07848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f139de2a28b]
[pkrvmxyh4eaekms:07848] [11] plumed(+0x15365)[0x55e16137d365]
[pkrvmxyh4eaekms:07848] *** End of error message ***
</pre>
{% endraw %}
