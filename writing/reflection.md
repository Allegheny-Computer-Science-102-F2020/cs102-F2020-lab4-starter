# Reflection by Gregory M. Kapfhammer

## Using a fenced code block, please display the correct output from running your program

TODO: Please provide a fenced code displaying the correct output from running your program

## Using a fenced code block, please display the passing output from running the tests

TODO: Please provide a fenced code with the passing output from running the tests

## What is the purpose of the following test case in the `test_summarize.py` file?

```
def test_summarize_empty_number_list():
    """Ensure that an empty list of numbers summarizes correctly."""
    data_list_numbers = []
    mean = summarize.compute_mean(data_list_numbers)
    assert math.isnan(mean)
```

TODO: Please write one paragraph that explains each line of code in this test case.

## What is the purpose of the following test case in the `test_transform.py` file?

```
def test_transform_empty_text_list_to_number_list():
    """Ensure that an empty list of textual numbers transforms correctly."""
    data_list_string = ""
    data_list_numbers = transform.transform_string_to_number_list(data_list_string)
    assert len(data_list_numbers) == 0
    assert sum(data_list_numbers) == 0
    assert data_list_numbers == []
```

TODO: Please write one paragraph that explains each line of code in this test case.

## What was the greatest technical challenge that you faced and how did you overcome it?

TODO: Please provide a detailed response to this question.

## After completing this assignment, what is one task that you want to practice more? Why?

TODO: Please provide a detailed response to this question.

## After completing this assignment, what is one experience for which you are grateful?

TODO: Please provide a detailed response to this question.

## Please use the following space to share any additional insights about the assignment, as needed

TODO: Please add any additional insights as needed, bearing in mind that this is not required.
