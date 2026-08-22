**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervm76f27:10372] *** Process received signal ***
[runnervm76f27:10372] Signal: Aborted (6)
[runnervm76f27:10372] Signal code:  (-6)
[runnervm76f27:10372] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65ebe45330]
[runnervm76f27:10372] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65ebe9ec0c]
[runnervm76f27:10372] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65ebe4527e]
[runnervm76f27:10372] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65ebe288ff]
[runnervm76f27:10372] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65ec2a5ff5]
[runnervm76f27:10372] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65ec2bb0da]
[runnervm76f27:10372] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65ec2a5a55]
[runnervm76f27:10372] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65ec2a5a6f]
[runnervm76f27:10372] [ 8] plumed_master(+0x146dd)[0x55e15f9d06dd]
[runnervm76f27:10372] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65ebe2a1ca]
[runnervm76f27:10372] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65ebe2a28b]
[runnervm76f27:10372] [11] plumed_master(+0x15365)[0x55e15f9d1365]
[runnervm76f27:10372] *** End of error message ***
</pre>
{% endraw %}
