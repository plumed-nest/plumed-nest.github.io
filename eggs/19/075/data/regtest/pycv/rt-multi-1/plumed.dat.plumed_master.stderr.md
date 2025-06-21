**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmxyh4eaekms:11615] *** Process received signal ***
[pkrvmxyh4eaekms:11615] Signal: Aborted (6)
[pkrvmxyh4eaekms:11615] Signal code:  (-6)
[pkrvmxyh4eaekms:11615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff516845330]
[pkrvmxyh4eaekms:11615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff51689eb2c]
[pkrvmxyh4eaekms:11615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff51684527e]
[pkrvmxyh4eaekms:11615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5168288ff]
[pkrvmxyh4eaekms:11615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff516ca5ff5]
[pkrvmxyh4eaekms:11615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff516cbb0da]
[pkrvmxyh4eaekms:11615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff516ca5a55]
[pkrvmxyh4eaekms:11615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff516ca5a6f]
[pkrvmxyh4eaekms:11615] [ 8] plumed_master(+0x146dd)[0x565323d496dd]
[pkrvmxyh4eaekms:11615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff51682a1ca]
[pkrvmxyh4eaekms:11615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff51682a28b]
[pkrvmxyh4eaekms:11615] [11] plumed_master(+0x15365)[0x565323d4a365]
[pkrvmxyh4eaekms:11615] *** End of error message ***
</pre>
{% endraw %}
