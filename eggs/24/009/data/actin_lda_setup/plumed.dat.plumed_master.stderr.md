**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmgx7h7:05101] *** Process received signal ***
[runnervmgx7h7:05101] Signal: Aborted (6)
[runnervmgx7h7:05101] Signal code:  (-6)
[runnervmgx7h7:05101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e31045330]
[runnervmgx7h7:05101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e3109ec0c]
[runnervmgx7h7:05101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e3104527e]
[runnervmgx7h7:05101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e310288ff]
[runnervmgx7h7:05101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e314a5ff5]
[runnervmgx7h7:05101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e314bb0da]
[runnervmgx7h7:05101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e314a5a55]
[runnervmgx7h7:05101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e314a5a6f]
[runnervmgx7h7:05101] [ 8] plumed_master(+0x146dd)[0x55df28b3d6dd]
[runnervmgx7h7:05101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e3102a1ca]
[runnervmgx7h7:05101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e3102a28b]
[runnervmgx7h7:05101] [11] plumed_master(+0x15365)[0x55df28b3e365]
[runnervmgx7h7:05101] *** End of error message ***
</pre>
{% endraw %}
