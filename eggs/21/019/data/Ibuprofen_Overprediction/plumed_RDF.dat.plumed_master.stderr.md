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
[runnervmi13qx:39956] *** Process received signal ***
[runnervmi13qx:39956] Signal: Aborted (6)
[runnervmi13qx:39956] Signal code:  (-6)
[runnervmi13qx:39956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80b1c45330]
[runnervmi13qx:39956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80b1c9eb2c]
[runnervmi13qx:39956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80b1c4527e]
[runnervmi13qx:39956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80b1c288ff]
[runnervmi13qx:39956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80b20a5ff5]
[runnervmi13qx:39956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80b20bb0da]
[runnervmi13qx:39956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80b20a5a55]
[runnervmi13qx:39956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80b20a5a6f]
[runnervmi13qx:39956] [ 8] plumed_master(+0x146dd)[0x55632df276dd]
[runnervmi13qx:39956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80b1c2a1ca]
[runnervmi13qx:39956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80b1c2a28b]
[runnervmi13qx:39956] [11] plumed_master(+0x15365)[0x55632df28365]
[runnervmi13qx:39956] *** End of error message ***
</pre>
{% endraw %}
