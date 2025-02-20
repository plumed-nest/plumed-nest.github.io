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
[fv-az797-511:07661] *** Process received signal ***
[fv-az797-511:07661] Signal: Aborted (6)
[fv-az797-511:07661] Signal code:  (-6)
[fv-az797-511:07661] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bf8245330]
[fv-az797-511:07661] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bf829eb2c]
[fv-az797-511:07661] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bf824527e]
[fv-az797-511:07661] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bf82288ff]
[fv-az797-511:07661] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bf86a5ff5]
[fv-az797-511:07661] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bf86bb0da]
[fv-az797-511:07661] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bf86a5a55]
[fv-az797-511:07661] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bf86a5a6f]
[fv-az797-511:07661] [ 8] plumed_master(+0x146dd)[0x5650f34536dd]
[fv-az797-511:07661] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bf822a1ca]
[fv-az797-511:07661] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bf822a28b]
[fv-az797-511:07661] [11] plumed_master(+0x15365)[0x5650f3454365]
[fv-az797-511:07661] *** End of error message ***
</pre>
{% endraw %}
