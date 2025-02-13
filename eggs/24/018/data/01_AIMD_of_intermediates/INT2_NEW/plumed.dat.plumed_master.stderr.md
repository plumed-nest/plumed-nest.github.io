**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:06186] *** Process received signal ***
[fv-az1280-696:06186] Signal: Aborted (6)
[fv-az1280-696:06186] Signal code:  (-6)
[fv-az1280-696:06186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1923a45330]
[fv-az1280-696:06186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1923a9eb2c]
[fv-az1280-696:06186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1923a4527e]
[fv-az1280-696:06186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1923a288ff]
[fv-az1280-696:06186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1923ea5ff5]
[fv-az1280-696:06186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1923ebb0da]
[fv-az1280-696:06186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1923ea5a55]
[fv-az1280-696:06186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1923ea5a6f]
[fv-az1280-696:06186] [ 8] plumed_master(+0x146dd)[0x55ed8bd9e6dd]
[fv-az1280-696:06186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1923a2a1ca]
[fv-az1280-696:06186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1923a2a28b]
[fv-az1280-696:06186] [11] plumed_master(+0x15365)[0x55ed8bd9f365]
[fv-az1280-696:06186] *** End of error message ***
</pre>
{% endraw %}
