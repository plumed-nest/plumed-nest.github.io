**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az1390-170:07370] *** Process received signal ***
[fv-az1390-170:07370] Signal: Aborted (6)
[fv-az1390-170:07370] Signal code:  (-6)
[fv-az1390-170:07370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5121045330]
[fv-az1390-170:07370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f512109eb2c]
[fv-az1390-170:07370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f512104527e]
[fv-az1390-170:07370] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51210288ff]
[fv-az1390-170:07370] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51214a5ff5]
[fv-az1390-170:07370] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51214bb0da]
[fv-az1390-170:07370] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51214a5a55]
[fv-az1390-170:07370] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51214a5a6f]
[fv-az1390-170:07370] [ 8] plumed(+0x146dd)[0x55e032d2d6dd]
[fv-az1390-170:07370] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f512102a1ca]
[fv-az1390-170:07370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f512102a28b]
[fv-az1390-170:07370] [11] plumed(+0x15365)[0x55e032d2e365]
[fv-az1390-170:07370] *** End of error message ***
</pre>
{% endraw %}
