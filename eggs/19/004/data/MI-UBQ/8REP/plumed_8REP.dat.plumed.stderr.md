**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/8REP/plumed_8REP.dat   
(download [zipped raw stdout](plumed_8REP.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f9c4309d4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f9c4309d428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f9c4309f02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f9c436d784d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f9c436d56b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f9c436d5701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f9c436d5919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f9c43088830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16542] *** End of error message ***
</pre>
{% endraw %}
