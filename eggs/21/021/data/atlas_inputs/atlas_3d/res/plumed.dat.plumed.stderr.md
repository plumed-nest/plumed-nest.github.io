**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1720-841:09001] *** Process received signal ***
[fv-az1720-841:09001] Signal: Aborted (6)
[fv-az1720-841:09001] Signal code:  (-6)
[fv-az1720-841:09001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ae5645330]
[fv-az1720-841:09001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ae569eb2c]
[fv-az1720-841:09001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ae564527e]
[fv-az1720-841:09001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ae56288ff]
[fv-az1720-841:09001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ae5aa5ff5]
[fv-az1720-841:09001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ae5abb0da]
[fv-az1720-841:09001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ae5aa5a55]
[fv-az1720-841:09001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ae5aa5a6f]
[fv-az1720-841:09001] [ 8] plumed(+0x146dd)[0x55bc6151b6dd]
[fv-az1720-841:09001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ae562a1ca]
[fv-az1720-841:09001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ae562a28b]
[fv-az1720-841:09001] [11] plumed(+0x15365)[0x55bc6151c365]
[fv-az1720-841:09001] *** End of error message ***
</pre>
{% endraw %}
