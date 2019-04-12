<template>
<div id="app">
    <form>
        <fieldset class="contactforms">
            <legend>
                Contact Me.
            </legend>
            <label>
                Full Name:
                <input type="text" name="name" size="30">
            </label>
            <br />
            <label>
                Email:
                <input type="text" name="email" size="30">
            </label>
            <br />
            <label>
                What Can I help you with?
                <br />
                <input class="asking" type="text" name="question" size="500">
            </label>
            <br />
            <button>Submit<input type="submit" name="submit"</button>
        </fieldset>
    </form>
</div>
</template>

<style scoped>
    .contactforms{
        margin:50px;
    }
    .asking{
        width: 500px;
        height: 200px;
    }
</style>