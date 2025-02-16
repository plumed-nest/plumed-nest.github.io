**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1979-234:62893] *** Process received signal ***
[fv-az1979-234:62893] Signal: Aborted (6)
[fv-az1979-234:62893] Signal code:  (-6)
[fv-az1979-234:62893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1235445330]
[fv-az1979-234:62893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f123549eb2c]
[fv-az1979-234:62893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f123544527e]
[fv-az1979-234:62893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12354288ff]
[fv-az1979-234:62893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12358a5ff5]
[fv-az1979-234:62893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12358bb0da]
[fv-az1979-234:62893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12358a5a55]
[fv-az1979-234:62893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12358a5a6f]
[fv-az1979-234:62893] [ 8] plumed_master(+0x146dd)[0x5610d0adc6dd]
[fv-az1979-234:62893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f123542a1ca]
[fv-az1979-234:62893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f123542a28b]
[fv-az1979-234:62893] [11] plumed_master(+0x15365)[0x5610d0add365]
[fv-az1979-234:62893] *** End of error message ***
</pre>
{% endraw %}
