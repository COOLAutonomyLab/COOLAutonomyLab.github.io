---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# <i class="fas fa-users"></i>Principal Investigator
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi, group: current"
%}

# <i class="fas fa-users"></i>Graduate Students
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ms, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot, group: current"
%}
{:.center}

{% include section.html %}


# <i class="fas fa-users"></i>Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ms, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: researcher, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: alumni"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot, group: alumni"
%}
{:.center}

