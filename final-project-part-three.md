| [home page](https://davidzouz.github.io/tswd-portfolio/) | [visualizing debt](https://davidzouz.github.io/tswd-portfolio/visualizing-government-debt) | [critique by design](https://davidzouz.github.io/tswd-portfolio/critique-by-design) | [final project I](https://davidzouz.github.io/tswd-portfolio/final-project-part-one) | [final project II](https://davidzouz.github.io/tswd-portfolio/final-project-part-two) | [final project III](https://davidzouz.github.io/tswd-portfolio/final-project-part-three) |

# The final data story
> Include a link to your final data story on Shorthand, Esri StoryMaps, etc. here. 

Tableau Full Story: https://public.tableau.com/app/profile/david.zou1201/viz/USUsedCarsDepreciationAnaysis/FullStory?publish=yes

<div class='tableauPlaceholder' id='viz1727829114403' style='position: relative'><noscript><a href='#'><img alt='Full Story ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USUsedCarsDepreciationAnaysis&#47;FullStory&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='USUsedCarsDepreciationAnaysis&#47;FullStory' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;US&#47;USUsedCarsDepreciationAnaysis&#47;FullStory&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>               
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1727829114403');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Changes made since Part II
>  Few paragraphs that reflects on changes you made since the completion of Part II.

Since the completion of Part II, I focused on refining both the narrative and the technical aspects of the dashboards to enhance the clarity and user engagement of the story-telling. The first change was **the development of a clear thesis statement: “Don’t Merely Consider Sedan/SUV/Electric Vehicle When Buying a Used Car.”** This change was introduced to address a key piece of feedback that the narrative lacked purpose and persuasion. By introducing this thesis, I provided the entire data story with a central guiding idea, allowing the visualizations and supporting data to connect back to this main point. The thesis gave the presentation a stronger argumentative structure, making it easier for the audience to follow the story and engage with the key insights.

I also responded to concerns about the overwhelming amount of information presented in certain dashboards. During Part II, some dashboards attempted to convey too many data points in a single view, making it hard for users to focus on specific insights. To address this, I **separated the more complex dashboards into two or more focused visualizations**, which made the data easier to digest. For example, I split a crowded dashboard that combined top/least depreciation brands and body style into separate ones, each focusing on a single and more accessible dimension.

Another critical design change was the introduction of **interactivity in the dashboard**. Based on feedback from interviews, users expressed a desire for a more personalized experience. I implemented interactive elements on the last dashboards, such as clickable filters, allowing users to drill down into specific data points, like depreciation rates by brand, body style, or the year of cars. This change not only made the dashboards more engaging but also gave users the flexibility to explore data that was most relevant to their needs, which utilized the functionanities of Tableau.

What's more, I made **simplification on the color scheme**. Feedback indicated that the original dashboards had too many different colors, which made it difficult for users to focus on key points. I reworked the visuals to use a consistent color palette, primarily blue and orange, which helped to unify the design across all dashboards.

In addition to these structural and design changes, I also **revised the content flow of the data story**. I adjusted the order of dashboards to create a more logical narrative progression, leading the audience from a high-level introduction of the used car market to more detailed and specific insights about car depreciation, body styles, and brands. This reorganization ensures that the audience can follow the story naturally.

## The audience
> Talk about who you identified as the audience for your final data story.

The primary audience for this project includes **potential used car buyers**, **car-related financial decision-makers**, and **automotive industry professionals**. These groups were identified through interviews and by analyzing common user personas, such as young buyers looking for affordable options with less depreciations and industry professionals interested in understanding car depreciation trends. Feedback from interviews help me narrow down the focus. For example, potential buyers were primarily concerned with prices, so put a lot of works on the data preparation process that I merged two datasets (one with the car MSRP, and another one with the current prices on the used car market) to calculate the vehicle remaining values, total depreciation rates, and the average depreciation rate per year to give the audience the direct information and insights.

To accommodate this diverse audience, I made specific adjustments, such as focusing on **key decision-making factors** like depreciation rates and vehicle remainding values, while also incorporating **interactive dashboards** that allow for deeper exploration of individual brands and car types. For industry professionals, I included broader **market trends with time-series forecasting** to help them understand used car pricing dynamics. These adjustments ensured that the data story would not only inform but also resonate with each segment of the audience.

## References:
> The only sources I used are the following two datasets from Kaggle

1. Used Car Price Prediction Dataset: https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset
2. Extended Dataset for Used Car Prices: https://www.kaggle.com/datasets/anthonytherrien/extended-dataset-for-used-car-prices-regression/data
