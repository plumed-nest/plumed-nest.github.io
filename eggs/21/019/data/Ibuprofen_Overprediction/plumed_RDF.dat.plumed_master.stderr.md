**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : it was not possible to interpret atom name ...
[runnervm76f27:10267] *** Process received signal ***
[runnervm76f27:10267] Signal: Aborted (6)
[runnervm76f27:10267] Signal code:  (-6)
[runnervm76f27:10267] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5a7645330]
[runnervm76f27:10267] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5a769ec0c]
[runnervm76f27:10267] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5a764527e]
[runnervm76f27:10267] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5a76288ff]
[runnervm76f27:10267] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5a7aa5ff5]
[runnervm76f27:10267] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5a7abb0da]
[runnervm76f27:10267] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5a7aa5a55]
[runnervm76f27:10267] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5a7aa5a6f]
[runnervm76f27:10267] [ 8] plumed_master(+0x146dd)[0x5601144936dd]
[runnervm76f27:10267] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5a762a1ca]
[runnervm76f27:10267] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5a762a28b]
[runnervm76f27:10267] [11] plumed_master(+0x15365)[0x560114494365]
[runnervm76f27:10267] *** End of error message ***
</pre>
{% endraw %}
