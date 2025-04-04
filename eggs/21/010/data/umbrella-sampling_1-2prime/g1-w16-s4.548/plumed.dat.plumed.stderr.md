**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1719-476:10776] *** Process received signal ***
[fv-az1719-476:10776] Signal: Aborted (6)
[fv-az1719-476:10776] Signal code:  (-6)
[fv-az1719-476:10776] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d21a45330]
[fv-az1719-476:10776] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d21a9eb2c]
[fv-az1719-476:10776] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d21a4527e]
[fv-az1719-476:10776] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d21a288ff]
[fv-az1719-476:10776] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d21ea5ff5]
[fv-az1719-476:10776] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d21ebb0da]
[fv-az1719-476:10776] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d21ea5a55]
[fv-az1719-476:10776] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d21ea5a6f]
[fv-az1719-476:10776] [ 8] plumed(+0x146dd)[0x561b41a346dd]
[fv-az1719-476:10776] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d21a2a1ca]
[fv-az1719-476:10776] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d21a2a28b]
[fv-az1719-476:10776] [11] plumed(+0x15365)[0x561b41a35365]
[fv-az1719-476:10776] *** End of error message ***
</pre>
{% endraw %}
