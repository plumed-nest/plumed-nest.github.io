**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmgx7h7:06428] *** Process received signal ***
[runnervmgx7h7:06428] Signal: Aborted (6)
[runnervmgx7h7:06428] Signal code:  (-6)
[runnervmgx7h7:06428] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0dec845330]
[runnervmgx7h7:06428] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0dec89ec0c]
[runnervmgx7h7:06428] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0dec84527e]
[runnervmgx7h7:06428] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0dec8288ff]
[runnervmgx7h7:06428] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0decca5ff5]
[runnervmgx7h7:06428] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0deccbb0da]
[runnervmgx7h7:06428] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0decca5a55]
[runnervmgx7h7:06428] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0decca5a6f]
[runnervmgx7h7:06428] [ 8] plumed_master(+0x146dd)[0x55a0e7bbc6dd]
[runnervmgx7h7:06428] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0dec82a1ca]
[runnervmgx7h7:06428] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0dec82a28b]
[runnervmgx7h7:06428] [11] plumed_master(+0x15365)[0x55a0e7bbd365]
[runnervmgx7h7:06428] *** End of error message ***
</pre>
{% endraw %}
