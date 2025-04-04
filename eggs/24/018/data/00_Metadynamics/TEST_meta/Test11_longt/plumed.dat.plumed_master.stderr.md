**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:06569] *** Process received signal ***
[fv-az1360-658:06569] Signal: Aborted (6)
[fv-az1360-658:06569] Signal code:  (-6)
[fv-az1360-658:06569] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f712be45330]
[fv-az1360-658:06569] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f712be9eb2c]
[fv-az1360-658:06569] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f712be4527e]
[fv-az1360-658:06569] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f712be288ff]
[fv-az1360-658:06569] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f712c2a5ff5]
[fv-az1360-658:06569] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f712c2bb0da]
[fv-az1360-658:06569] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f712c2a5a55]
[fv-az1360-658:06569] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f712c2a5a6f]
[fv-az1360-658:06569] [ 8] plumed_master(+0x146dd)[0x55febfb3f6dd]
[fv-az1360-658:06569] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f712be2a1ca]
[fv-az1360-658:06569] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f712be2a28b]
[fv-az1360-658:06569] [11] plumed_master(+0x15365)[0x55febfb40365]
[fv-az1360-658:06569] *** End of error message ***
</pre>
{% endraw %}
