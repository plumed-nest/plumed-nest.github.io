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
[pkrvm7jw40e0xgp:06607] *** Process received signal ***
[pkrvm7jw40e0xgp:06607] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06607] Signal code:  (-6)
[pkrvm7jw40e0xgp:06607] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b53445330]
[pkrvm7jw40e0xgp:06607] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b5349eb2c]
[pkrvm7jw40e0xgp:06607] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b5344527e]
[pkrvm7jw40e0xgp:06607] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b534288ff]
[pkrvm7jw40e0xgp:06607] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b538a5ff5]
[pkrvm7jw40e0xgp:06607] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b538bb0da]
[pkrvm7jw40e0xgp:06607] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b538a5a55]
[pkrvm7jw40e0xgp:06607] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b538a5a6f]
[pkrvm7jw40e0xgp:06607] [ 8] plumed_master(+0x146dd)[0x5654d948f6dd]
[pkrvm7jw40e0xgp:06607] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b5342a1ca]
[pkrvm7jw40e0xgp:06607] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b5342a28b]
[pkrvm7jw40e0xgp:06607] [11] plumed_master(+0x15365)[0x5654d9490365]
[pkrvm7jw40e0xgp:06607] *** End of error message ***
</pre>
{% endraw %}
