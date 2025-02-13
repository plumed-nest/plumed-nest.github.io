**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1390-170:10974] *** Process received signal ***
[fv-az1390-170:10974] Signal: Aborted (6)
[fv-az1390-170:10974] Signal code:  (-6)
[fv-az1390-170:10974] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc620e45330]
[fv-az1390-170:10974] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc620e9eb2c]
[fv-az1390-170:10974] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc620e4527e]
[fv-az1390-170:10974] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc620e288ff]
[fv-az1390-170:10974] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6212a5ff5]
[fv-az1390-170:10974] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6212bb0da]
[fv-az1390-170:10974] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6212a5a55]
[fv-az1390-170:10974] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6212a5a6f]
[fv-az1390-170:10974] [ 8] plumed(+0x146dd)[0x5564545316dd]
[fv-az1390-170:10974] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc620e2a1ca]
[fv-az1390-170:10974] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc620e2a28b]
[fv-az1390-170:10974] [11] plumed(+0x15365)[0x556454532365]
[fv-az1390-170:10974] *** End of error message ***
</pre>
{% endraw %}
