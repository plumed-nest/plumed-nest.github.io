**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:64884] *** Process received signal ***
[fv-az1701-508:64884] Signal: Aborted (6)
[fv-az1701-508:64884] Signal code:  (-6)
[fv-az1701-508:64884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d94245330]
[fv-az1701-508:64884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d9429eb2c]
[fv-az1701-508:64884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d9424527e]
[fv-az1701-508:64884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d942288ff]
[fv-az1701-508:64884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d946a5ff5]
[fv-az1701-508:64884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d946bb0da]
[fv-az1701-508:64884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d946a5a55]
[fv-az1701-508:64884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d946a5a6f]
[fv-az1701-508:64884] [ 8] plumed(+0x146dd)[0x55dddef8b6dd]
[fv-az1701-508:64884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d9422a1ca]
[fv-az1701-508:64884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d9422a28b]
[fv-az1701-508:64884] [11] plumed(+0x15365)[0x55dddef8c365]
[fv-az1701-508:64884] *** End of error message ***
</pre>
{% endraw %}
