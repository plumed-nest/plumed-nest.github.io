**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:06664] *** Process received signal ***
[pkrvmpptgkbjq6m:06664] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06664] Signal code:  (-6)
[pkrvmpptgkbjq6m:06664] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f308b045330]
[pkrvmpptgkbjq6m:06664] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f308b09eb2c]
[pkrvmpptgkbjq6m:06664] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f308b04527e]
[pkrvmpptgkbjq6m:06664] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f308b0288ff]
[pkrvmpptgkbjq6m:06664] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f308b4a5ff5]
[pkrvmpptgkbjq6m:06664] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f308b4bb0da]
[pkrvmpptgkbjq6m:06664] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f308b4a5a55]
[pkrvmpptgkbjq6m:06664] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f308b4a5a6f]
[pkrvmpptgkbjq6m:06664] [ 8] plumed_master(+0x146dd)[0x55e094b296dd]
[pkrvmpptgkbjq6m:06664] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f308b02a1ca]
[pkrvmpptgkbjq6m:06664] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f308b02a28b]
[pkrvmpptgkbjq6m:06664] [11] plumed_master(+0x15365)[0x55e094b2a365]
[pkrvmpptgkbjq6m:06664] *** End of error message ***
</pre>
{% endraw %}
