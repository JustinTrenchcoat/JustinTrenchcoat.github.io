---
layout: page
title: Maximizing Dealership Profitability
description: The project that introduced me to decision-making
img: /assets/img/compare_budget.png
importance: 1
category: work
related_publications: false
---
This is nothing but a course project on Combinatorial Optimization, where the group have to utilize every bit of learnt knowledge and apply it to a real-world problem. This project is under the context of maximizing profit of a used-car dealership(not a real one, of course!) by managing the number of cars to buy in, constraint by budget and storage size. Our group utilzied both linear programming solver and heuristics algorithms (I wrote two of them!), and compared their performance.

<div class="row">
    <div class="col-md mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/algo_fuel.png" title="algo image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/greedy_budget_fuel_type.png" title="budget" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/greedy_size_fuel_type.png" title="size" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Given a fixed constraint, each solver gives a different answer.
</div>

Just to make the problem a little bit more challenging, we also asked for two more specific constraints: 
1. if the bought cars has any imported cars, there is a one-time licensing fee the dealership has to pay
2. if the bought cars has any hybrid cars, there is a one-time infrastruction fee the dealership has to pay to upgrade their storage lot with charger posts!

Below is the performance comparison between two greedy algorithms.
<div class="row">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/compare_budget.png" title="Comparison of Greedy Algo, varying Budget" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/compare_capacity_2.png" title="Comparison of Greedy Algo, varying Capacity" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Number of Cars sold by two greedy algorithms, varying budget (Top) and parking lot size (Down) constraint from zero to total size of all available cars
</div>

The link to project repository is [Here](https://github.com/JustinTrenchcoat/MATH441_Project_2)
