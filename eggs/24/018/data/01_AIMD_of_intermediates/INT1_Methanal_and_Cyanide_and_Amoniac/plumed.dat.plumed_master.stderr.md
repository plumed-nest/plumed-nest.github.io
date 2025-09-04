**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07872] *** Process received signal ***
[pkrvm7jw40e0xgp:07872] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07872] Signal code:  (-6)
[pkrvm7jw40e0xgp:07872] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc08c45330]
[pkrvm7jw40e0xgp:07872] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc08c9eb2c]
[pkrvm7jw40e0xgp:07872] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc08c4527e]
[pkrvm7jw40e0xgp:07872] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc08c288ff]
[pkrvm7jw40e0xgp:07872] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc090a5ff5]
[pkrvm7jw40e0xgp:07872] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc090bb0da]
[pkrvm7jw40e0xgp:07872] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc090a5a55]
[pkrvm7jw40e0xgp:07872] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc090a5a6f]
[pkrvm7jw40e0xgp:07872] [ 8] plumed_master(+0x146dd)[0x558d2d22e6dd]
[pkrvm7jw40e0xgp:07872] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc08c2a1ca]
[pkrvm7jw40e0xgp:07872] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc08c2a28b]
[pkrvm7jw40e0xgp:07872] [11] plumed_master(+0x15365)[0x558d2d22f365]
[pkrvm7jw40e0xgp:07872] *** End of error message ***
</pre>
{% endraw %}
