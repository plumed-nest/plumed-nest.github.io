**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07975] *** Process received signal ***
[pkrvm7jw40e0xgp:07975] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07975] Signal code:  (-6)
[pkrvm7jw40e0xgp:07975] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0e8845330]
[pkrvm7jw40e0xgp:07975] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0e889eb2c]
[pkrvm7jw40e0xgp:07975] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0e884527e]
[pkrvm7jw40e0xgp:07975] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0e88288ff]
[pkrvm7jw40e0xgp:07975] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0e8ca5ff5]
[pkrvm7jw40e0xgp:07975] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0e8cbb0da]
[pkrvm7jw40e0xgp:07975] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0e8ca5a55]
[pkrvm7jw40e0xgp:07975] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0e8ca5a6f]
[pkrvm7jw40e0xgp:07975] [ 8] plumed_master(+0x146dd)[0x55bab6a746dd]
[pkrvm7jw40e0xgp:07975] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0e882a1ca]
[pkrvm7jw40e0xgp:07975] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0e882a28b]
[pkrvm7jw40e0xgp:07975] [11] plumed_master(+0x15365)[0x55bab6a75365]
[pkrvm7jw40e0xgp:07975] *** End of error message ***
</pre>
{% endraw %}
