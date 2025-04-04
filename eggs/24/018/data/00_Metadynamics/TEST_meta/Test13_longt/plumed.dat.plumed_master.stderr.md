**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:06672] *** Process received signal ***
[fv-az1360-658:06672] Signal: Aborted (6)
[fv-az1360-658:06672] Signal code:  (-6)
[fv-az1360-658:06672] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc57645330]
[fv-az1360-658:06672] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc5769eb2c]
[fv-az1360-658:06672] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc5764527e]
[fv-az1360-658:06672] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc576288ff]
[fv-az1360-658:06672] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc57aa5ff5]
[fv-az1360-658:06672] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc57abb0da]
[fv-az1360-658:06672] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc57aa5a55]
[fv-az1360-658:06672] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc57aa5a6f]
[fv-az1360-658:06672] [ 8] plumed_master(+0x146dd)[0x564b3db906dd]
[fv-az1360-658:06672] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc5762a1ca]
[fv-az1360-658:06672] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc5762a28b]
[fv-az1360-658:06672] [11] plumed_master(+0x15365)[0x564b3db91365]
[fv-az1360-658:06672] *** End of error message ***
</pre>
{% endraw %}
