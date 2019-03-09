# unknown-heroes


Code or Console Example Blocks
------------------------------
If you have example code or console text that you want to appear with
all line breaks and relative indentation preserved, in a monospaced text
block, there is no common format for Markdown and reStructuredText, but
you can combine the formatting for both of them by ending one paragraph
with a double colon ``::`` (for reStructuredText) and indenting the next
one by four or more spaces (for Markdown) to make it appear in
monospaced font without flow or word-wrapping::

    A normal paragraph ending with ``::`` will flow and be word-wrapped::

        If the next paragraph is indented by four or more spaces, it will be monospaced text, without flow (or even wrapping in some non-print cases.)

        You can have multiple paragraphs like this, as long as they
        are all indented by the same amount.
