**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[fv-az1370-99:64500] *** Process received signal ***
[fv-az1370-99:64500] Signal: Aborted (6)
[fv-az1370-99:64500] Signal code:  (-6)
[fv-az1370-99:64500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd1fe45330]
[fv-az1370-99:64500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd1fe9eb2c]
[fv-az1370-99:64500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd1fe4527e]
[fv-az1370-99:64500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd1fe288ff]
[fv-az1370-99:64500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd202a5ff5]
[fv-az1370-99:64500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd202bb0da]
[fv-az1370-99:64500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd202a5a55]
[fv-az1370-99:64500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd202a5a6f]
[fv-az1370-99:64500] [ 8] plumed(+0x146dd)[0x562b1bece6dd]
[fv-az1370-99:64500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd1fe2a1ca]
[fv-az1370-99:64500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd1fe2a28b]
[fv-az1370-99:64500] [11] plumed(+0x15365)[0x562b1becf365]
[fv-az1370-99:64500] *** End of error message ***
</pre>
{% endraw %}
