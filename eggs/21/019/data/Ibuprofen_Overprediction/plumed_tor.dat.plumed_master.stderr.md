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
[fv-az1983-395:65065] *** Process received signal ***
[fv-az1983-395:65065] Signal: Aborted (6)
[fv-az1983-395:65065] Signal code:  (-6)
[fv-az1983-395:65065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06a3045330]
[fv-az1983-395:65065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06a309eb2c]
[fv-az1983-395:65065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06a304527e]
[fv-az1983-395:65065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06a30288ff]
[fv-az1983-395:65065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06a34a5ff5]
[fv-az1983-395:65065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06a34bb0da]
[fv-az1983-395:65065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06a34a5a55]
[fv-az1983-395:65065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06a34a5a6f]
[fv-az1983-395:65065] [ 8] plumed_master(+0x146dd)[0x55f2674a36dd]
[fv-az1983-395:65065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06a302a1ca]
[fv-az1983-395:65065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06a302a28b]
[fv-az1983-395:65065] [11] plumed_master(+0x15365)[0x55f2674a4365]
[fv-az1983-395:65065] *** End of error message ***
</pre>
{% endraw %}
