**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07819] *** Process received signal ***
[pkrvm7jw40e0xgp:07819] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07819] Signal code:  (-6)
[pkrvm7jw40e0xgp:07819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f757f845330]
[pkrvm7jw40e0xgp:07819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f757f89eb2c]
[pkrvm7jw40e0xgp:07819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f757f84527e]
[pkrvm7jw40e0xgp:07819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f757f8288ff]
[pkrvm7jw40e0xgp:07819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f757fca5ff5]
[pkrvm7jw40e0xgp:07819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f757fcbb0da]
[pkrvm7jw40e0xgp:07819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f757fca5a55]
[pkrvm7jw40e0xgp:07819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f757fca5a6f]
[pkrvm7jw40e0xgp:07819] [ 8] plumed_master(+0x146dd)[0x55ab6bcdd6dd]
[pkrvm7jw40e0xgp:07819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f757f82a1ca]
[pkrvm7jw40e0xgp:07819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f757f82a28b]
[pkrvm7jw40e0xgp:07819] [11] plumed_master(+0x15365)[0x55ab6bcde365]
[pkrvm7jw40e0xgp:07819] *** End of error message ***
</pre>
{% endraw %}
