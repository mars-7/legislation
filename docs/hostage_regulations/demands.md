---
sidebar_position: 2
title: Demands
---

export const Highlight = ({children, color, text}) => (
<span
style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: text ? text : '#fff',
      padding: '0.2rem',
    }}>
{children}
</span>
);

## Points

To be able to utilize your hostages you must first have a certain number of points, each clearance level has a different number of points. Below is a table of what each clearance level is worth in terms of these points.

| Clearance | Points |
| ----------------- | ------------------------ |
| <Highlight color="#cccccc">**Security Class 0**</Highlight> | +1 |
| <Highlight color="#ffff00">**Security Class 1**</Highlight> | +2 |
| <Highlight color="#f1c232">**Security Class 2**</Highlight> | +4 |
| <Highlight color="#0084ff">**Security Class 3**</Highlight> | +16 |
| <Highlight color="#e13238">**Security Class 4**</Highlight> | +32 |
| <Highlight color="#e13238">**Installation Director**</Highlight> | +70 |
| <Highlight color="#e13238">**O5 Council**</Highlight> | +100 |

## Acceptable Demands

After you have taken some hostages you can request for a demand given in the table below. Each amount of points can be redeemed for anything below or at the amount of points you have, to elaborate on this if you were to have 2 SC-4’s you’d have 64 points which would allow you to request for anything that’s between 50-89 points such as a Keter Class anomaly.

| Points | Requestable Demands | Explanation/Restrictions |
| ----------------- | ------------------- | ------------------------ |
| 0-5 | Food items | N/A |
| 6-10 | Vehicles (Unarmoured) | N/A |
| 11-29 | Safe Class Anomalies<br/>Unarmed Humvees<br/>Free Roam | Anything that is a Safe Class SCP<br/>Free roam for 10 minutes |
| 30-49 | Euclid Class Anomalies<br/>Armed Humvees<br/>Free Roam | Anything that is a Euclid Class SCP<br/>Any form of vehicle<br/>Free roam for 30 minutes |
| 90-99 | Alpha Class SCP’s<br/> | Anything that is an Alpha Class SCP |
| 100+ | Anything, at O5 discretion | N/A |