**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmxyh4eaekms:11963] *** Process received signal ***
[pkrvmxyh4eaekms:11963] Signal: Aborted (6)
[pkrvmxyh4eaekms:11963] Signal code:  (-6)
[pkrvmxyh4eaekms:11963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e7b845330]
[pkrvmxyh4eaekms:11963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e7b89eb2c]
[pkrvmxyh4eaekms:11963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e7b84527e]
[pkrvmxyh4eaekms:11963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e7b8288ff]
[pkrvmxyh4eaekms:11963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e7bca5ff5]
[pkrvmxyh4eaekms:11963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e7bcbb0da]
[pkrvmxyh4eaekms:11963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e7bca5a55]
[pkrvmxyh4eaekms:11963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e7bca5a6f]
[pkrvmxyh4eaekms:11963] [ 8] plumed_master(+0x146dd)[0x558ade2056dd]
[pkrvmxyh4eaekms:11963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e7b82a1ca]
[pkrvmxyh4eaekms:11963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e7b82a28b]
[pkrvmxyh4eaekms:11963] [11] plumed_master(+0x15365)[0x558ade206365]
[pkrvmxyh4eaekms:11963] *** End of error message ***
</pre>
{% endraw %}
