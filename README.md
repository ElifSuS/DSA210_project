# The Impact of Stress on Song-Skipping Habits: A Data Analysis Project
This project explores the relationship between stress and the tendency to skip songs using Spotify data.

My objectives are to investigate whether stressful periods lead to increased song skipping and analyze and visualize patterns in total listening time and song
skipping behavior during stressful and non-stressful periods.

I believe there might be a scientific relationship between stress and song-skipping behavior based on factors such as Cognitive Load Theory (stress increases cognitive load, reducing the brain's ability to focus on complex or unfamiliar stimuli), Attention Span Reduction, and the Need for Predictability (stress can heighten the need for familiarity and predictability, causing unpredictable songs to be skipped more often as they require more cognitive effort to process).

The dataset is generated from Spotify's streaming history, including:
Artist name, album name, date, skip information.

Data Analysis: Techniques and Stages:
I loaded the data into a pandas DataFrame for analysis. I preprocessed the data. I summarized and visualized the total listening time for each year. Then I Counted and visualized how many songs were skipped each month. To determine whether stress affects the number of skipped songs, I performed t-test to compare the means. I visualized them via bar plots.

Stressful periods are predefined as specific months based on my final exam periods.

Hypothesis Testing
- Null Hypothesis (H₀): Stress does not influence the number of skipped songs.
-Alternative Hypothesis (H₁): Stress leads to a significant change in song-skipping behavior.

Conclusion:
Based on the current dataset, there is no significant relationship between stress levels and the average number of skipped songs.
