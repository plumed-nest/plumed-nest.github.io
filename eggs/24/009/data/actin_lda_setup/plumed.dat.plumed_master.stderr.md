**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvmxyh4eaekms:07683] *** Process received signal ***
[pkrvmxyh4eaekms:07683] Signal: Aborted (6)
[pkrvmxyh4eaekms:07683] Signal code:  (-6)
[pkrvmxyh4eaekms:07683] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c31c45330]
[pkrvmxyh4eaekms:07683] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c31c9eb2c]
[pkrvmxyh4eaekms:07683] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c31c4527e]
[pkrvmxyh4eaekms:07683] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c31c288ff]
[pkrvmxyh4eaekms:07683] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c320a5ff5]
[pkrvmxyh4eaekms:07683] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c320bb0da]
[pkrvmxyh4eaekms:07683] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c320a5a55]
[pkrvmxyh4eaekms:07683] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c320a5a6f]
[pkrvmxyh4eaekms:07683] [ 8] plumed_master(+0x146dd)[0x55ff6fd226dd]
[pkrvmxyh4eaekms:07683] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c31c2a1ca]
[pkrvmxyh4eaekms:07683] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c31c2a28b]
[pkrvmxyh4eaekms:07683] [11] plumed_master(+0x15365)[0x55ff6fd23365]
[pkrvmxyh4eaekms:07683] *** End of error message ***
</pre>
{% endraw %}
