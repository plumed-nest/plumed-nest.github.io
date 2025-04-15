**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1719-82:65991] *** Process received signal ***
[fv-az1719-82:65991] Signal: Aborted (6)
[fv-az1719-82:65991] Signal code:  (-6)
[fv-az1719-82:65991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd75b645330]
[fv-az1719-82:65991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd75b69eb2c]
[fv-az1719-82:65991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd75b64527e]
[fv-az1719-82:65991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd75b6288ff]
[fv-az1719-82:65991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd75baa5ff5]
[fv-az1719-82:65991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd75babb0da]
[fv-az1719-82:65991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd75baa5a55]
[fv-az1719-82:65991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd75baa5a6f]
[fv-az1719-82:65991] [ 8] plumed(+0x146dd)[0x5555c13a66dd]
[fv-az1719-82:65991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd75b62a1ca]
[fv-az1719-82:65991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd75b62a28b]
[fv-az1719-82:65991] [11] plumed(+0x15365)[0x5555c13a7365]
[fv-az1719-82:65991] *** End of error message ***
</pre>
{% endraw %}
