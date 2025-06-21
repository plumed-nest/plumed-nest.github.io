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
[pkrvmxyh4eaekms:08063] *** Process received signal ***
[pkrvmxyh4eaekms:08063] Signal: Aborted (6)
[pkrvmxyh4eaekms:08063] Signal code:  (-6)
[pkrvmxyh4eaekms:08063] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f454ee45330]
[pkrvmxyh4eaekms:08063] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f454ee9eb2c]
[pkrvmxyh4eaekms:08063] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f454ee4527e]
[pkrvmxyh4eaekms:08063] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f454ee288ff]
[pkrvmxyh4eaekms:08063] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f454f2a5ff5]
[pkrvmxyh4eaekms:08063] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f454f2bb0da]
[pkrvmxyh4eaekms:08063] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f454f2a5a55]
[pkrvmxyh4eaekms:08063] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f454f2a5a6f]
[pkrvmxyh4eaekms:08063] [ 8] plumed_master(+0x146dd)[0x561b927146dd]
[pkrvmxyh4eaekms:08063] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f454ee2a1ca]
[pkrvmxyh4eaekms:08063] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f454ee2a28b]
[pkrvmxyh4eaekms:08063] [11] plumed_master(+0x15365)[0x561b92715365]
[pkrvmxyh4eaekms:08063] *** End of error message ***
</pre>
{% endraw %}
