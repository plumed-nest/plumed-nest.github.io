**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1267-279:65961] *** Process received signal ***
[fv-az1267-279:65961] Signal: Aborted (6)
[fv-az1267-279:65961] Signal code:  (-6)
[fv-az1267-279:65961] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad6e845330]
[fv-az1267-279:65961] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad6e89eb2c]
[fv-az1267-279:65961] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad6e84527e]
[fv-az1267-279:65961] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad6e8288ff]
[fv-az1267-279:65961] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad6eca5ff5]
[fv-az1267-279:65961] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad6ecbb0da]
[fv-az1267-279:65961] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad6eca5a55]
[fv-az1267-279:65961] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad6eca5a6f]
[fv-az1267-279:65961] [ 8] plumed(+0x146dd)[0x55ddce07b6dd]
[fv-az1267-279:65961] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad6e82a1ca]
[fv-az1267-279:65961] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad6e82a28b]
[fv-az1267-279:65961] [11] plumed(+0x15365)[0x55ddce07c365]
[fv-az1267-279:65961] *** End of error message ***
</pre>
{% endraw %}
