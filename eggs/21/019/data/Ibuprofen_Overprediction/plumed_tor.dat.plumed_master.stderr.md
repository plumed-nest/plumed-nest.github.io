**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[pkrvmpptgkbjq6m:10526] *** Process received signal ***
[pkrvmpptgkbjq6m:10526] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10526] Signal code:  (-6)
[pkrvmpptgkbjq6m:10526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a27845330]
[pkrvmpptgkbjq6m:10526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a2789eb2c]
[pkrvmpptgkbjq6m:10526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a2784527e]
[pkrvmpptgkbjq6m:10526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a278288ff]
[pkrvmpptgkbjq6m:10526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a27ca5ff5]
[pkrvmpptgkbjq6m:10526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a27cbb0da]
[pkrvmpptgkbjq6m:10526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a27ca5a55]
[pkrvmpptgkbjq6m:10526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a27ca5a6f]
[pkrvmpptgkbjq6m:10526] [ 8] plumed_master(+0x146dd)[0x55add903b6dd]
[pkrvmpptgkbjq6m:10526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a2782a1ca]
[pkrvmpptgkbjq6m:10526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a2782a28b]
[pkrvmpptgkbjq6m:10526] [11] plumed_master(+0x15365)[0x55add903c365]
[pkrvmpptgkbjq6m:10526] *** End of error message ***
</pre>
{% endraw %}
