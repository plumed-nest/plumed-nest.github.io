**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:60942] *** Process received signal ***
[fv-az787-589:60942] Signal: Aborted (6)
[fv-az787-589:60942] Signal code:  (-6)
[fv-az787-589:60942] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8ecc45330]
[fv-az787-589:60942] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8ecc9eb2c]
[fv-az787-589:60942] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8ecc4527e]
[fv-az787-589:60942] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8ecc288ff]
[fv-az787-589:60942] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8ed0a5ff5]
[fv-az787-589:60942] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8ed0bb0da]
[fv-az787-589:60942] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8ed0a5a55]
[fv-az787-589:60942] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8ed0a5a6f]
[fv-az787-589:60942] [ 8] plumed(+0x146dd)[0x55cf1464e6dd]
[fv-az787-589:60942] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8ecc2a1ca]
[fv-az787-589:60942] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8ecc2a28b]
[fv-az787-589:60942] [11] plumed(+0x15365)[0x55cf1464f365]
[fv-az787-589:60942] *** End of error message ***
</pre>
{% endraw %}
