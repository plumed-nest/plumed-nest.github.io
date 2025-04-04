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
[fv-az805-507:11626] *** Process received signal ***
[fv-az805-507:11626] Signal: Aborted (6)
[fv-az805-507:11626] Signal code:  (-6)
[fv-az805-507:11626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a79c45330]
[fv-az805-507:11626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a79c9eb2c]
[fv-az805-507:11626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a79c4527e]
[fv-az805-507:11626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a79c288ff]
[fv-az805-507:11626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a7a0a5ff5]
[fv-az805-507:11626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a7a0bb0da]
[fv-az805-507:11626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a7a0a5a55]
[fv-az805-507:11626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a7a0a5a6f]
[fv-az805-507:11626] [ 8] plumed(+0x146dd)[0x5581d7f046dd]
[fv-az805-507:11626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a79c2a1ca]
[fv-az805-507:11626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a79c2a28b]
[fv-az805-507:11626] [11] plumed(+0x15365)[0x5581d7f05365]
[fv-az805-507:11626] *** End of error message ***
</pre>
{% endraw %}
