**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmpptgkbjq6m:12821] *** Process received signal ***
[pkrvmpptgkbjq6m:12821] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12821] Signal code:  (-6)
[pkrvmpptgkbjq6m:12821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b8cc45330]
[pkrvmpptgkbjq6m:12821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b8cc9eb2c]
[pkrvmpptgkbjq6m:12821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b8cc4527e]
[pkrvmpptgkbjq6m:12821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b8cc288ff]
[pkrvmpptgkbjq6m:12821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b8d0a5ff5]
[pkrvmpptgkbjq6m:12821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b8d0bb0da]
[pkrvmpptgkbjq6m:12821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b8d0a5a55]
[pkrvmpptgkbjq6m:12821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b8d0a5a6f]
[pkrvmpptgkbjq6m:12821] [ 8] plumed_master(+0x146dd)[0x562f051da6dd]
[pkrvmpptgkbjq6m:12821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b8cc2a1ca]
[pkrvmpptgkbjq6m:12821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b8cc2a28b]
[pkrvmpptgkbjq6m:12821] [11] plumed_master(+0x15365)[0x562f051db365]
[pkrvmpptgkbjq6m:12821] *** End of error message ***
</pre>
{% endraw %}
