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
[fv-az789-879:66709] *** Process received signal ***
[fv-az789-879:66709] Signal: Aborted (6)
[fv-az789-879:66709] Signal code:  (-6)
[fv-az789-879:66709] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f102e045330]
[fv-az789-879:66709] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f102e09eb2c]
[fv-az789-879:66709] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f102e04527e]
[fv-az789-879:66709] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f102e0288ff]
[fv-az789-879:66709] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f102e4a5ff5]
[fv-az789-879:66709] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f102e4bb0da]
[fv-az789-879:66709] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f102e4a5a55]
[fv-az789-879:66709] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f102e4a5a6f]
[fv-az789-879:66709] [ 8] plumed(+0x146dd)[0x56514d6b56dd]
[fv-az789-879:66709] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f102e02a1ca]
[fv-az789-879:66709] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f102e02a28b]
[fv-az789-879:66709] [11] plumed(+0x15365)[0x56514d6b6365]
[fv-az789-879:66709] *** End of error message ***
</pre>
{% endraw %}
