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
[fv-az1050-229:65029] *** Process received signal ***
[fv-az1050-229:65029] Signal: Aborted (6)
[fv-az1050-229:65029] Signal code:  (-6)
[fv-az1050-229:65029] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f768a245330]
[fv-az1050-229:65029] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f768a29eb2c]
[fv-az1050-229:65029] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f768a24527e]
[fv-az1050-229:65029] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f768a2288ff]
[fv-az1050-229:65029] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f768a6a5ff5]
[fv-az1050-229:65029] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f768a6bb0da]
[fv-az1050-229:65029] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f768a6a5a55]
[fv-az1050-229:65029] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f768a6a5a6f]
[fv-az1050-229:65029] [ 8] plumed_master(+0x146dd)[0x5557271f06dd]
[fv-az1050-229:65029] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f768a22a1ca]
[fv-az1050-229:65029] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f768a22a28b]
[fv-az1050-229:65029] [11] plumed_master(+0x15365)[0x5557271f1365]
[fv-az1050-229:65029] *** End of error message ***
</pre>
{% endraw %}
