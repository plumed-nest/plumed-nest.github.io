**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1719-82:66043] *** Process received signal ***
[fv-az1719-82:66043] Signal: Aborted (6)
[fv-az1719-82:66043] Signal code:  (-6)
[fv-az1719-82:66043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee47645330]
[fv-az1719-82:66043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee4769eb2c]
[fv-az1719-82:66043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee4764527e]
[fv-az1719-82:66043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee476288ff]
[fv-az1719-82:66043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee47aa5ff5]
[fv-az1719-82:66043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee47abb0da]
[fv-az1719-82:66043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee47aa5a55]
[fv-az1719-82:66043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee47aa5a6f]
[fv-az1719-82:66043] [ 8] plumed(+0x146dd)[0x562e86bae6dd]
[fv-az1719-82:66043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee4762a1ca]
[fv-az1719-82:66043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee4762a28b]
[fv-az1719-82:66043] [11] plumed(+0x15365)[0x562e86baf365]
[fv-az1719-82:66043] *** End of error message ***
</pre>
{% endraw %}
