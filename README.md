# PersistLab

Our website is based on the open source templates designed and shared by the labs of [D. Allan Drummond](http://www.allanlab.org/aboutwebsite.html) and [Trevor Bedford](http://bedford.io/misc/about/). We downloaded source codes from their repository and modified our contents based on shared templates. We greatly thank for Allan and Trevor for allowing reuse of their codebase. 

The website is deployed using [GitHub Pages]() and the source code is available on [GitHub](). Please feel free to reuse this code (making sure to cite the Bedford lab and Drummond lab as the original sources of the lab website template).


Update process: 
1. After clone the persist-lab.github.io to local, run ```bundle exec jekyll serve --trace``` 
2. Access localhost:4000 and make corresponding changes.
3. Build packages ```bundle exec jekyll build --destination docs``` 
3. under persist-lab.github.io/docs/css, replace the main.css with persist-lab.github.io/reserved_css/main.css. Somehow, the built main.css has fewer contents than expected. I'll do more investigation later. For now, we can use the reserved_css/main.css.
4. Push the updates to github.