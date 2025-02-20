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
[fv-az797-511:07645] *** Process received signal ***
[fv-az797-511:07645] Signal: Aborted (6)
[fv-az797-511:07645] Signal code:  (-6)
[fv-az797-511:07645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a7b845330]
[fv-az797-511:07645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a7b89eb2c]
[fv-az797-511:07645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a7b84527e]
[fv-az797-511:07645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a7b8288ff]
[fv-az797-511:07645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a7bca5ff5]
[fv-az797-511:07645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a7bcbb0da]
[fv-az797-511:07645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a7bca5a55]
[fv-az797-511:07645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a7bca5a6f]
[fv-az797-511:07645] [ 8] plumed(+0x146dd)[0x563451b1e6dd]
[fv-az797-511:07645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a7b82a1ca]
[fv-az797-511:07645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a7b82a28b]
[fv-az797-511:07645] [11] plumed(+0x15365)[0x563451b1f365]
[fv-az797-511:07645] *** End of error message ***
</pre>
{% endraw %}
