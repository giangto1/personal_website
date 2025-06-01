---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: base2
title: Projects
---
<style>
.project-card img {
  height: 140px; /* or any fixed height */
  object-fit: cover;
  width: 100%;
  display: block;
}

.project-card h3 {
  height: 48px;  /* adjust based on font-size and lines */
  overflow: hidden;
  margin-top: 10px;
}

.project-card p {
  height: 96px;  /* or use line-clamp for multi-line trimming */
  overflow: hidden;
  margin: 10px 0;
}

.project-card .tag {
  margin-top: auto; /* pushes to bottom if using flex column */
}

</style>
<section style="width: 100%; padding: 0 20px; margin: 0;">
 
<div style="display: flex; flex-wrap: wrap; justify-content: flex-start; gap: 15px;">
    <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://github.com/giangto1/DataViz2025" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/dataviz.png" style="width: 100%; height: auto; padding: 5px;">
    <h3 style='font-size: 15px;'><b>DataViz 2025: Is Park Fee related to Visitor count?</b></h3>
        <p style='font-size: 14px;'>This project is a submission for the competition DataViz 2025 Love Data Week competition, which investigates the connection between national park recreational visitor count and entry fees.</p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #fff;">Data Visualization</span>
    </div>
    </a>
    </article>

    <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://public.tableau.com/app/profile/giang.to/viz/oil_17356781135850/Dashboard1" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/oil.png" style="width: 100%; height: auto; padding: 5px;">
    <h3 style='font-size: 15px;'><b>Oil Imports and Exports Visualization</b></h3>
        <p style='font-size: 14px;'>This interactive Tableau dashboard analyzes global oil production and consumption trends, highlighting key metrics such as country-wise production, consumption rates, and reserves. </p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #fff;">Data Visualization</span>
    </div>
    </a>
    </article>

    <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://github.com/giangto1/5525Chess" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/chess.png" style="width: 100%; height: auto; padding: 5px;">
    <h3 style='font-size: 15px; padding: 3px; margin-top: 20px;'><b>Classifying Chess Pieces</b></h3>
        <p style='font-size: 14px;'>This project focuses on implementing Support Vector Machines (SVM) for image classification of chess pieces. It includes utilizing Scikit-learn's SVM implementation and building a custom SVM from scratch to compare performance and accuracy.</p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #fff;">Machine Learning</span>
    </div>
    </a>
    </article>

    <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://docs.google.com/presentation/d/1uwwbQubfv1tSXSgcNdC6HYvtEotF9khndNf-g7csbL0/edit?slide=id.p#slide=id.p" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/agi2.png" style="width: 100%; height: auto; padding: 5px;">
    <h3 style='font-size: 15px;'><b>4th place winner AGI Hackathon: Study App Analysis</b></h3>
        <p style='font-size: 14px;'>Analysing TABot features to determine the key factor boosting academic success, made recommendations on optimizing the app's UI, ways to increase student interaction with the app, and develop marketing strategies for retaining and recruiting users.</p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #fff;">Data Analytics</span>
    </div>
    </a>
    </article>

    <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://github.com/giangto1/DataViz2025" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/sql-challenge.png" style="width: 100%; height: auto; padding: 5px; margin-top: 30px;">
    <h3 style='font-size: 15px; margin-top: 30px; margin-bottom: 30px;'><b>8 Weeks SQL Challenge</b></h3>
        <p style='font-size: 14px;'>This repository contains solutions for the 8 case studies from the #8WeekSQLChallenge. It highlights my ability to solve diverse SQL problems while showcasing my expertise in SQL query writing and analytical problem-solving.</p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #ffffff;">Data Analytics</span>
    </div>
    </a>
    </article>

        <article style="width:25%; margin-bottom: 24px; text-align: left; border: 1px solid #ccc; border-radius: 10px; box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08); padding: 20px;">
    <a href="https://giangto1.github.io/csci5541-NLP-FinalProject-TheParsingPals/" style='color: #000000; text-decoration: none;'>
    <img src="/assets/img/teaser.png" style="width: 100%; height: auto;">
    <h3 style='font-size: 15px;'><b>Speech-to-Text: Translate Dialects to Official Vietnamese Language</b></h3>
        <p style='font-size: 14px;'>Developed a pipeline that transcribes dialectal Vietnamese speech into standardized Vietnamese text – instead of providing a direct word-for-word transcription, the system generates standard Vietnamese using finetuned PhoWhisper and PhoBERT. </p>
    <div style="display: inline-block; background-color: rgb(32, 133, 167); border-radius: 6px; padding: 4px 8px;">
        <span style="font-size: 13px; color: #ffffff;">NLP</span>
    </div>
    </a>
    </article>

</div>

</section>