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
[fv-az789-879:66656] *** Process received signal ***
[fv-az789-879:66656] Signal: Aborted (6)
[fv-az789-879:66656] Signal code:  (-6)
[fv-az789-879:66656] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e30a45330]
[fv-az789-879:66656] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e30a9eb2c]
[fv-az789-879:66656] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e30a4527e]
[fv-az789-879:66656] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e30a288ff]
[fv-az789-879:66656] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e30ea5ff5]
[fv-az789-879:66656] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e30ebb0da]
[fv-az789-879:66656] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e30ea5a55]
[fv-az789-879:66656] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e30ea5a6f]
[fv-az789-879:66656] [ 8] plumed(+0x146dd)[0x561a27f626dd]
[fv-az789-879:66656] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e30a2a1ca]
[fv-az789-879:66656] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e30a2a28b]
[fv-az789-879:66656] [11] plumed(+0x15365)[0x561a27f63365]
[fv-az789-879:66656] *** End of error message ***
</pre>
{% endraw %}
