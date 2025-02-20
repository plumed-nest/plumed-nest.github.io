**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az816-356:10968] *** Process received signal ***
[fv-az816-356:10968] Signal: Aborted (6)
[fv-az816-356:10968] Signal code:  (-6)
[fv-az816-356:10968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5545445330]
[fv-az816-356:10968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f554549eb2c]
[fv-az816-356:10968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f554544527e]
[fv-az816-356:10968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55454288ff]
[fv-az816-356:10968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55458a5ff5]
[fv-az816-356:10968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55458bb0da]
[fv-az816-356:10968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55458a5a55]
[fv-az816-356:10968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55458a5a6f]
[fv-az816-356:10968] [ 8] plumed_master(+0x146dd)[0x55ec2101b6dd]
[fv-az816-356:10968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f554542a1ca]
[fv-az816-356:10968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f554542a28b]
[fv-az816-356:10968] [11] plumed_master(+0x15365)[0x55ec2101c365]
[fv-az816-356:10968] *** End of error message ***
</pre>
{% endraw %}
