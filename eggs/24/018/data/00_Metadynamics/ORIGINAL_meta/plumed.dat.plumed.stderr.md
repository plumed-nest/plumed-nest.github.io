**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:05598] *** Process received signal ***
[fv-az1444-322:05598] Signal: Aborted (6)
[fv-az1444-322:05598] Signal code:  (-6)
[fv-az1444-322:05598] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24d7645330]
[fv-az1444-322:05598] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24d769eb2c]
[fv-az1444-322:05598] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24d764527e]
[fv-az1444-322:05598] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24d76288ff]
[fv-az1444-322:05598] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24d7aa5ff5]
[fv-az1444-322:05598] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24d7abb0da]
[fv-az1444-322:05598] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24d7aa5a55]
[fv-az1444-322:05598] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24d7aa5a6f]
[fv-az1444-322:05598] [ 8] plumed(+0x146dd)[0x55eaf1a116dd]
[fv-az1444-322:05598] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24d762a1ca]
[fv-az1444-322:05598] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24d762a28b]
[fv-az1444-322:05598] [11] plumed(+0x15365)[0x55eaf1a12365]
[fv-az1444-322:05598] *** End of error message ***
</pre>
{% endraw %}
