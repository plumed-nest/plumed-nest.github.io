**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1719-82:66250] *** Process received signal ***
[fv-az1719-82:66250] Signal: Aborted (6)
[fv-az1719-82:66250] Signal code:  (-6)
[fv-az1719-82:66250] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a3aa45330]
[fv-az1719-82:66250] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a3aa9eb2c]
[fv-az1719-82:66250] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a3aa4527e]
[fv-az1719-82:66250] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a3aa288ff]
[fv-az1719-82:66250] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a3aea5ff5]
[fv-az1719-82:66250] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a3aebb0da]
[fv-az1719-82:66250] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a3aea5a55]
[fv-az1719-82:66250] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a3aea5a6f]
[fv-az1719-82:66250] [ 8] plumed(+0x146dd)[0x5649821026dd]
[fv-az1719-82:66250] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a3aa2a1ca]
[fv-az1719-82:66250] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a3aa2a28b]
[fv-az1719-82:66250] [11] plumed(+0x15365)[0x564982103365]
[fv-az1719-82:66250] *** End of error message ***
</pre>
{% endraw %}
