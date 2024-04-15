<h1>Cricket Project Team</h1>
 
<i>Padma Danturty, Ian Loree, Bryce Carson, Aryan Shah, Sam Dorfman, & Maddie Coe</i>

Cricket is one of the most popular sports in the world, yet some of us don’t even know the rules! Which leads us to believe that there is so much potential for cricket analytics in the US. Why wait for someone else to do it?

Our group's work was conducted in the <code>cricket_stats.ipynb</code> and <code>visualize.ipynb</code> Jupyter notebooks, using 1200 simulations based on T20I matches through April 7th, 2024, and our presentation slides from the Winter 2024 semester are included.

<h3>Setup</h3>
Run the following: <pre><code>python3 -m venv env
source env/bin/activate 
pip install -r requirements.txt</code></pre> to create a virtual environment and download necessary packages with pip. You can run the <code>get_files.ipynb</code> Jupyter notebook to download the latest T20 International cricket match data from <a href="cricsheet.org">Cricsheet</a> and organize it into a csv file for analysis. Otherwise, match data through the date of the latest commit is provided in <code>merged_files.csv</code>, with information from Cricsheet about the included matches in <code>matches_info.txt</code>.