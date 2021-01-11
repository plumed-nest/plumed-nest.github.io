**Project ID:** [plumID:19.012]({{ '/' | absolute_url }}eggs/19/012/)  
Stderr for source:  ./Protein-DNA/plumed-main.dat   
(download [zipped raw stdout](plumed-main.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (saxsdata\.biasDer)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f764ef424b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f764ef42428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f764ef4402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f764f57c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f764f57a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f764f57a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f764f57a919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f764ef2d830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16323] *** End of error message ***
</pre>
{% endraw %}
