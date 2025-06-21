**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmxyh4eaekms:11201] *** Process received signal ***
[pkrvmxyh4eaekms:11201] Signal: Aborted (6)
[pkrvmxyh4eaekms:11201] Signal code:  (-6)
[pkrvmxyh4eaekms:11201] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f283e045330]
[pkrvmxyh4eaekms:11201] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f283e09eb2c]
[pkrvmxyh4eaekms:11201] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f283e04527e]
[pkrvmxyh4eaekms:11201] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f283e0288ff]
[pkrvmxyh4eaekms:11201] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f283e4a5ff5]
[pkrvmxyh4eaekms:11201] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f283e4bb0da]
[pkrvmxyh4eaekms:11201] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f283e4a5a55]
[pkrvmxyh4eaekms:11201] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f283e4a5a6f]
[pkrvmxyh4eaekms:11201] [ 8] plumed_master(+0x146dd)[0x55659129f6dd]
[pkrvmxyh4eaekms:11201] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f283e02a1ca]
[pkrvmxyh4eaekms:11201] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f283e02a28b]
[pkrvmxyh4eaekms:11201] [11] plumed_master(+0x15365)[0x5565912a0365]
[pkrvmxyh4eaekms:11201] *** End of error message ***
</pre>
{% endraw %}
