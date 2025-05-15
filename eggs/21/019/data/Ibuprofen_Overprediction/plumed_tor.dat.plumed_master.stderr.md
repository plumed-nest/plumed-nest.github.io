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
[pkrvmberfyhpb9w:09337] *** Process received signal ***
[pkrvmberfyhpb9w:09337] Signal: Aborted (6)
[pkrvmberfyhpb9w:09337] Signal code:  (-6)
[pkrvmberfyhpb9w:09337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb21b645330]
[pkrvmberfyhpb9w:09337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21b69eb2c]
[pkrvmberfyhpb9w:09337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21b64527e]
[pkrvmberfyhpb9w:09337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb21b6288ff]
[pkrvmberfyhpb9w:09337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb21baa5ff5]
[pkrvmberfyhpb9w:09337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb21babb0da]
[pkrvmberfyhpb9w:09337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb21baa5a55]
[pkrvmberfyhpb9w:09337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb21baa5a6f]
[pkrvmberfyhpb9w:09337] [ 8] plumed_master(+0x146dd)[0x5620bb8196dd]
[pkrvmberfyhpb9w:09337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21b62a1ca]
[pkrvmberfyhpb9w:09337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21b62a28b]
[pkrvmberfyhpb9w:09337] [11] plumed_master(+0x15365)[0x5620bb81a365]
[pkrvmberfyhpb9w:09337] *** End of error message ***
</pre>
{% endraw %}
