**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvm7jw40e0xgp:06592] *** Process received signal ***
[pkrvm7jw40e0xgp:06592] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06592] Signal code:  (-6)
[pkrvm7jw40e0xgp:06592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe148c45330]
[pkrvm7jw40e0xgp:06592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe148c9eb2c]
[pkrvm7jw40e0xgp:06592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe148c4527e]
[pkrvm7jw40e0xgp:06592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe148c288ff]
[pkrvm7jw40e0xgp:06592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1490a5ff5]
[pkrvm7jw40e0xgp:06592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1490bb0da]
[pkrvm7jw40e0xgp:06592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1490a5a55]
[pkrvm7jw40e0xgp:06592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1490a5a6f]
[pkrvm7jw40e0xgp:06592] [ 8] plumed(+0x146dd)[0x55ec831cb6dd]
[pkrvm7jw40e0xgp:06592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe148c2a1ca]
[pkrvm7jw40e0xgp:06592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe148c2a28b]
[pkrvm7jw40e0xgp:06592] [11] plumed(+0x15365)[0x55ec831cc365]
[pkrvm7jw40e0xgp:06592] *** End of error message ***
</pre>
{% endraw %}
