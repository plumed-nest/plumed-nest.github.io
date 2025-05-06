**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1050-229:61707] *** Process received signal ***
[fv-az1050-229:61707] Signal: Aborted (6)
[fv-az1050-229:61707] Signal code:  (-6)
[fv-az1050-229:61707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa709245330]
[fv-az1050-229:61707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa70929eb2c]
[fv-az1050-229:61707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa70924527e]
[fv-az1050-229:61707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7092288ff]
[fv-az1050-229:61707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7096a5ff5]
[fv-az1050-229:61707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7096bb0da]
[fv-az1050-229:61707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7096a5a55]
[fv-az1050-229:61707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7096a5a6f]
[fv-az1050-229:61707] [ 8] plumed_master(+0x146dd)[0x55f59608a6dd]
[fv-az1050-229:61707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa70922a1ca]
[fv-az1050-229:61707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa70922a28b]
[fv-az1050-229:61707] [11] plumed_master(+0x15365)[0x55f59608b365]
[fv-az1050-229:61707] *** End of error message ***
</pre>
{% endraw %}
