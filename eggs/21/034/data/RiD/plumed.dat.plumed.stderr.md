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
[fv-az1719-82:65512] *** Process received signal ***
[fv-az1719-82:65512] Signal: Aborted (6)
[fv-az1719-82:65512] Signal code:  (-6)
[fv-az1719-82:65512] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd692845330]
[fv-az1719-82:65512] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd69289eb2c]
[fv-az1719-82:65512] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd69284527e]
[fv-az1719-82:65512] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6928288ff]
[fv-az1719-82:65512] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd692ca5ff5]
[fv-az1719-82:65512] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd692cbb0da]
[fv-az1719-82:65512] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd692ca5a55]
[fv-az1719-82:65512] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd692ca5a6f]
[fv-az1719-82:65512] [ 8] plumed(+0x146dd)[0x55c906bc76dd]
[fv-az1719-82:65512] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd69282a1ca]
[fv-az1719-82:65512] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd69282a28b]
[fv-az1719-82:65512] [11] plumed(+0x15365)[0x55c906bc8365]
[fv-az1719-82:65512] *** End of error message ***
</pre>
{% endraw %}
