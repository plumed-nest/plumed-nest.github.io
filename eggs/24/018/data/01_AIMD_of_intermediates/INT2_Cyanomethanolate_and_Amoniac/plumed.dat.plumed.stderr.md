**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1442-469:04294] *** Process received signal ***
[fv-az1442-469:04294] Signal: Aborted (6)
[fv-az1442-469:04294] Signal code:  (-6)
[fv-az1442-469:04294] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3f4e042520]
[fv-az1442-469:04294] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3f4e0969fc]
[fv-az1442-469:04294] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3f4e042476]
[fv-az1442-469:04294] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3f4e0287f3]
[fv-az1442-469:04294] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3f4e4a2b9e]
[fv-az1442-469:04294] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3f4e4ae20c]
[fv-az1442-469:04294] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3f4e4ae277]
[fv-az1442-469:04294] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3f4e4ae52b]
[fv-az1442-469:04294] [ 8] plumed(+0x14254)[0x55b3d7a50254]
[fv-az1442-469:04294] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3f4e029d90]
[fv-az1442-469:04294] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3f4e029e40]
[fv-az1442-469:04294] [11] plumed(+0x14eb5)[0x55b3d7a50eb5]
[fv-az1442-469:04294] *** End of error message ***
</pre>
{% endraw %}