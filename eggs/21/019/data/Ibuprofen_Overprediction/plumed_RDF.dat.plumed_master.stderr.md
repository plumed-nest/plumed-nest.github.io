**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : it was not possible to interpret atom name ...
[runnervm0kj6c:09591] *** Process received signal ***
[runnervm0kj6c:09591] Signal: Aborted (6)
[runnervm0kj6c:09591] Signal code:  (-6)
[runnervm0kj6c:09591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f0f645330]
[runnervm0kj6c:09591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f0f69eb2c]
[runnervm0kj6c:09591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f0f64527e]
[runnervm0kj6c:09591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f0f6288ff]
[runnervm0kj6c:09591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f0faa5ff5]
[runnervm0kj6c:09591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f0fabb0da]
[runnervm0kj6c:09591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f0faa5a55]
[runnervm0kj6c:09591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f0faa5a6f]
[runnervm0kj6c:09591] [ 8] plumed_master(+0x146dd)[0x55f998f9e6dd]
[runnervm0kj6c:09591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f0f62a1ca]
[runnervm0kj6c:09591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f0f62a28b]
[runnervm0kj6c:09591] [11] plumed_master(+0x15365)[0x55f998f9f365]
[runnervm0kj6c:09591] *** End of error message ***
</pre>
{% endraw %}
