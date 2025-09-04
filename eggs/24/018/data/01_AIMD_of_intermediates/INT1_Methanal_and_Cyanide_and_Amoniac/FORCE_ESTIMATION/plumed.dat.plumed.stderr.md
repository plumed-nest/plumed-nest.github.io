**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07752] *** Process received signal ***
[pkrvm7jw40e0xgp:07752] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07752] Signal code:  (-6)
[pkrvm7jw40e0xgp:07752] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4061a45330]
[pkrvm7jw40e0xgp:07752] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4061a9eb2c]
[pkrvm7jw40e0xgp:07752] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4061a4527e]
[pkrvm7jw40e0xgp:07752] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4061a288ff]
[pkrvm7jw40e0xgp:07752] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4061ea5ff5]
[pkrvm7jw40e0xgp:07752] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4061ebb0da]
[pkrvm7jw40e0xgp:07752] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4061ea5a55]
[pkrvm7jw40e0xgp:07752] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4061ea5a6f]
[pkrvm7jw40e0xgp:07752] [ 8] plumed(+0x146dd)[0x5561eee6b6dd]
[pkrvm7jw40e0xgp:07752] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4061a2a1ca]
[pkrvm7jw40e0xgp:07752] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4061a2a28b]
[pkrvm7jw40e0xgp:07752] [11] plumed(+0x15365)[0x5561eee6c365]
[pkrvm7jw40e0xgp:07752] *** End of error message ***
</pre>
{% endraw %}
