**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1979-234:62823] *** Process received signal ***
[fv-az1979-234:62823] Signal: Aborted (6)
[fv-az1979-234:62823] Signal code:  (-6)
[fv-az1979-234:62823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f88045330]
[fv-az1979-234:62823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f8809eb2c]
[fv-az1979-234:62823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f8804527e]
[fv-az1979-234:62823] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f880288ff]
[fv-az1979-234:62823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f884a5ff5]
[fv-az1979-234:62823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f884bb0da]
[fv-az1979-234:62823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f884a5a55]
[fv-az1979-234:62823] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f884a5a6f]
[fv-az1979-234:62823] [ 8] plumed(+0x146dd)[0x55ca78a536dd]
[fv-az1979-234:62823] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f8802a1ca]
[fv-az1979-234:62823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f8802a28b]
[fv-az1979-234:62823] [11] plumed(+0x15365)[0x55ca78a54365]
[fv-az1979-234:62823] *** End of error message ***
</pre>
{% endraw %}
