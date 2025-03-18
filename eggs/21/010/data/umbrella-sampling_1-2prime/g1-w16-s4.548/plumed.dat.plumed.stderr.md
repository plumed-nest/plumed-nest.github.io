**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az790-36:66498] *** Process received signal ***
[fv-az790-36:66498] Signal: Aborted (6)
[fv-az790-36:66498] Signal code:  (-6)
[fv-az790-36:66498] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01b9c45330]
[fv-az790-36:66498] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01b9c9eb2c]
[fv-az790-36:66498] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01b9c4527e]
[fv-az790-36:66498] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01b9c288ff]
[fv-az790-36:66498] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01ba0a5ff5]
[fv-az790-36:66498] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01ba0bb0da]
[fv-az790-36:66498] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01ba0a5a55]
[fv-az790-36:66498] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01ba0a5a6f]
[fv-az790-36:66498] [ 8] plumed(+0x146dd)[0x5558982be6dd]
[fv-az790-36:66498] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01b9c2a1ca]
[fv-az790-36:66498] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01b9c2a28b]
[fv-az790-36:66498] [11] plumed(+0x15365)[0x5558982bf365]
[fv-az790-36:66498] *** End of error message ***
</pre>
{% endraw %}
