**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az816-356:10952] *** Process received signal ***
[fv-az816-356:10952] Signal: Aborted (6)
[fv-az816-356:10952] Signal code:  (-6)
[fv-az816-356:10952] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4aaf445330]
[fv-az816-356:10952] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4aaf49eb2c]
[fv-az816-356:10952] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4aaf44527e]
[fv-az816-356:10952] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4aaf4288ff]
[fv-az816-356:10952] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4aaf8a5ff5]
[fv-az816-356:10952] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4aaf8bb0da]
[fv-az816-356:10952] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4aaf8a5a55]
[fv-az816-356:10952] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4aaf8a5a6f]
[fv-az816-356:10952] [ 8] plumed(+0x146dd)[0x55bbaac4f6dd]
[fv-az816-356:10952] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4aaf42a1ca]
[fv-az816-356:10952] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4aaf42a28b]
[fv-az816-356:10952] [11] plumed(+0x15365)[0x55bbaac50365]
[fv-az816-356:10952] *** End of error message ***
</pre>
{% endraw %}
