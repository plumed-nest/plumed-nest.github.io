**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:09687] *** Process received signal ***
[runnervm76f27:09687] Signal: Aborted (6)
[runnervm76f27:09687] Signal code:  (-6)
[runnervm76f27:09687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe66a845330]
[runnervm76f27:09687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe66a89ec0c]
[runnervm76f27:09687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe66a84527e]
[runnervm76f27:09687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe66a8288ff]
[runnervm76f27:09687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe66aca5ff5]
[runnervm76f27:09687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe66acbb0da]
[runnervm76f27:09687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe66aca5a55]
[runnervm76f27:09687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe66aca5a6f]
[runnervm76f27:09687] [ 8] plumed(+0x146dd)[0x557bd317c6dd]
[runnervm76f27:09687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe66a82a1ca]
[runnervm76f27:09687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe66a82a28b]
[runnervm76f27:09687] [11] plumed(+0x15365)[0x557bd317d365]
[runnervm76f27:09687] *** End of error message ***
</pre>
{% endraw %}
