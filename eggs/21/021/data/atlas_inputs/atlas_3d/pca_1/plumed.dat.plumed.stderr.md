**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:64730] *** Process received signal ***
[fv-az1701-508:64730] Signal: Aborted (6)
[fv-az1701-508:64730] Signal code:  (-6)
[fv-az1701-508:64730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6fcea45330]
[fv-az1701-508:64730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6fcea9eb2c]
[fv-az1701-508:64730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6fcea4527e]
[fv-az1701-508:64730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6fcea288ff]
[fv-az1701-508:64730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6fceea5ff5]
[fv-az1701-508:64730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6fceebb0da]
[fv-az1701-508:64730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6fceea5a55]
[fv-az1701-508:64730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6fceea5a6f]
[fv-az1701-508:64730] [ 8] plumed(+0x146dd)[0x563d2c0416dd]
[fv-az1701-508:64730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6fcea2a1ca]
[fv-az1701-508:64730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6fcea2a28b]
[fv-az1701-508:64730] [11] plumed(+0x15365)[0x563d2c042365]
[fv-az1701-508:64730] *** End of error message ***
</pre>
{% endraw %}
