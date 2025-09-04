**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07856] *** Process received signal ***
[pkrvm7jw40e0xgp:07856] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07856] Signal code:  (-6)
[pkrvm7jw40e0xgp:07856] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4840c45330]
[pkrvm7jw40e0xgp:07856] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4840c9eb2c]
[pkrvm7jw40e0xgp:07856] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4840c4527e]
[pkrvm7jw40e0xgp:07856] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4840c288ff]
[pkrvm7jw40e0xgp:07856] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48410a5ff5]
[pkrvm7jw40e0xgp:07856] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48410bb0da]
[pkrvm7jw40e0xgp:07856] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48410a5a55]
[pkrvm7jw40e0xgp:07856] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48410a5a6f]
[pkrvm7jw40e0xgp:07856] [ 8] plumed(+0x146dd)[0x55b59a0be6dd]
[pkrvm7jw40e0xgp:07856] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4840c2a1ca]
[pkrvm7jw40e0xgp:07856] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4840c2a28b]
[pkrvm7jw40e0xgp:07856] [11] plumed(+0x15365)[0x55b59a0bf365]
[pkrvm7jw40e0xgp:07856] *** End of error message ***
</pre>
{% endraw %}
