**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w20-s5.412/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1390-170:10818] *** Process received signal ***
[fv-az1390-170:10818] Signal: Aborted (6)
[fv-az1390-170:10818] Signal code:  (-6)
[fv-az1390-170:10818] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23ce445330]
[fv-az1390-170:10818] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23ce49eb2c]
[fv-az1390-170:10818] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23ce44527e]
[fv-az1390-170:10818] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23ce4288ff]
[fv-az1390-170:10818] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23ce8a5ff5]
[fv-az1390-170:10818] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23ce8bb0da]
[fv-az1390-170:10818] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23ce8a5a55]
[fv-az1390-170:10818] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23ce8a5a6f]
[fv-az1390-170:10818] [ 8] plumed(+0x146dd)[0x5566e3f156dd]
[fv-az1390-170:10818] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23ce42a1ca]
[fv-az1390-170:10818] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23ce42a28b]
[fv-az1390-170:10818] [11] plumed(+0x15365)[0x5566e3f16365]
[fv-az1390-170:10818] *** End of error message ***
</pre>
{% endraw %}
