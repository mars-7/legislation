---
sidebar_position: 2
title: Chain of Command
---

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

<Highlight color="#000000">Manufacturing Oversight</Highlight>

The Manufacturing Department Oversight consists of <Highlight color="#000000">The Administrator</Highlight>, <Highlight color="#000000">MaD Overseer</Highlight>, and the <Highlight color="#9f2f30">Technical Installation Director</Highlight>. 

<Highlight color="#f9c149">Manufacturing Secretary</Highlight>

Manufacturing Secretaries act as the Coordinating Staff for the Quality Assurance Team and as such reserve complete Command authority over the team. Secretaries are responsible for the onboarding of, hiring of, and disciplining of Quality Assurance staff.

<Highlight color="#493a2a">Development Staff</Highlight>

While developers hold no command authority over Quality Assurance often times developers will need QA testers to test specific portions of their task or the overall project. As such Development Staff are permitted to request QA and guide them in the correct route.

<Highlight color="#9f5bb2">QA Tester</Highlight>

Quality Assurance Testers are responsible for finding and reporting issues within Manufacturing Department projects.
