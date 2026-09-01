**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmgx7h7:06483] *** Process received signal ***
[runnervmgx7h7:06483] Signal: Aborted (6)
[runnervmgx7h7:06483] Signal code:  (-6)
[runnervmgx7h7:06483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f18a6645330]
[runnervmgx7h7:06483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f18a669ec0c]
[runnervmgx7h7:06483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f18a664527e]
[runnervmgx7h7:06483] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18a66288ff]
[runnervmgx7h7:06483] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18a6aa5ff5]
[runnervmgx7h7:06483] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18a6abb0da]
[runnervmgx7h7:06483] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18a6aa5a55]
[runnervmgx7h7:06483] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18a6aa5a6f]
[runnervmgx7h7:06483] [ 8] plumed_master(+0x146dd)[0x556ced8b06dd]
[runnervmgx7h7:06483] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f18a662a1ca]
[runnervmgx7h7:06483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f18a662a28b]
[runnervmgx7h7:06483] [11] plumed_master(+0x15365)[0x556ced8b1365]
[runnervmgx7h7:06483] *** End of error message ***
</pre>
{% endraw %}
