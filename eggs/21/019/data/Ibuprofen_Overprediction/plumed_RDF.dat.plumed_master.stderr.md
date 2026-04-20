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
[runnervmeorf1:07975] *** Process received signal ***
[runnervmeorf1:07975] Signal: Aborted (6)
[runnervmeorf1:07975] Signal code:  (-6)
[runnervmeorf1:07975] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30b6a45330]
[runnervmeorf1:07975] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30b6a9eb2c]
[runnervmeorf1:07975] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30b6a4527e]
[runnervmeorf1:07975] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30b6a288ff]
[runnervmeorf1:07975] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30b6ea5ff5]
[runnervmeorf1:07975] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30b6ebb0da]
[runnervmeorf1:07975] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30b6ea5a55]
[runnervmeorf1:07975] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30b6ea5a6f]
[runnervmeorf1:07975] [ 8] plumed_master(+0x146dd)[0x55a5977266dd]
[runnervmeorf1:07975] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30b6a2a1ca]
[runnervmeorf1:07975] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30b6a2a28b]
[runnervmeorf1:07975] [11] plumed_master(+0x15365)[0x55a597727365]
[runnervmeorf1:07975] *** End of error message ***
</pre>
{% endraw %}
