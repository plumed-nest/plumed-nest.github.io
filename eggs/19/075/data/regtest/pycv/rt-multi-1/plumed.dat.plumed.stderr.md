**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1665-105:15087] *** Process received signal ***
[fv-az1665-105:15087] Signal: Aborted (6)
[fv-az1665-105:15087] Signal code:  (-6)
[fv-az1665-105:15087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8d4645330]
[fv-az1665-105:15087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8d469eb2c]
[fv-az1665-105:15087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8d464527e]
[fv-az1665-105:15087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8d46288ff]
[fv-az1665-105:15087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8d4aa5ff5]
[fv-az1665-105:15087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8d4abb0da]
[fv-az1665-105:15087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8d4aa5a55]
[fv-az1665-105:15087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8d4aa5a6f]
[fv-az1665-105:15087] [ 8] plumed(+0x146dd)[0x5625970666dd]
[fv-az1665-105:15087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8d462a1ca]
[fv-az1665-105:15087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8d462a28b]
[fv-az1665-105:15087] [11] plumed(+0x15365)[0x562597067365]
[fv-az1665-105:15087] *** End of error message ***
</pre>
{% endraw %}
