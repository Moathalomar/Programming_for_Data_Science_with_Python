$git diff
diff --git a/bikeshare.py
b/bikeshare.py
index cd1d149..f4c041f 100644
--- a/bikeshare.py
+++ b/bikeshare.py
@@ -16,6 +16,10 @@ weekdays =
('sunday', 'monday', 'tuesday',
'wednesday', 'thursday', 'friday',
def choice(prompt, choices=('y',
'n')):
"""Return a valid input from the
user given an array of possible
answers.
+
+ Args:
+ (str) prompt - prompt with
input request
+ (tup) choices - tuple with
elements of possible answers
"""
$ git diff
diff --git a/README.md
b/README.md
index 13a6e85..bb56def 100644
--- a/README.md
+++ b/README.md
@@ -5,6 +5,18 @@
### Description
This is a CLI program developed to
allow the user to explore an US
bikeshare system database and
retrieve statistics information from
the database. The user is able filter
the information by city, month and
weekday, in order to visualize
statistics information related to a
specific subset of data.
+#### Getting Started
+
+This program is structured in 2
steps.
+
+In a first moment, the user selects
the filters that are going to be
applied to the database. The user is
able to chose as many filters as it
would like.
+
+After this step, the DataFrame for
the analysis is created based on the
filters chosen by the user.
+
+In a second moment, the user is
able to chose, from a list of options,
the statistics the user would like to
calculate, based on the available
filtered data.
+
+As of April 2, 2019 the user is now
able to chose to view raw data and
also able sort this data by columns,
in ascending or descending order.

