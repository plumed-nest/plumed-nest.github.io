**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:64018] *** Process received signal ***
[fv-az1377-740:64018] Signal: Aborted (6)
[fv-az1377-740:64018] Signal code:  (-6)
[fv-az1377-740:64018] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a76045330]
[fv-az1377-740:64018] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a7609eb2c]
[fv-az1377-740:64018] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a7604527e]
[fv-az1377-740:64018] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a760288ff]
[fv-az1377-740:64018] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a764a5ff5]
[fv-az1377-740:64018] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a764bb0da]
[fv-az1377-740:64018] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a764a5a55]
[fv-az1377-740:64018] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a764a5a6f]
[fv-az1377-740:64018] [ 8] plumed(+0x146dd)[0x55f748e356dd]
[fv-az1377-740:64018] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a7602a1ca]
[fv-az1377-740:64018] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a7602a28b]
[fv-az1377-740:64018] [11] plumed(+0x15365)[0x55f748e36365]
[fv-az1377-740:64018] *** End of error message ***
</pre>
{% endraw %}
