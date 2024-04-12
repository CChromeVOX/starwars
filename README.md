## starwars

 Structure of the App was made in initial commit

 Second step is about convenient url system, we use 

 # async getResource(url) {
        const res = await fetch(this._apiBase + url);
        if(!res.ok)
            throw new Error(`Could not fetch ${url}, received ${res.status}`);
        return await res.json();
    }
#
this method in all other in order to fetch data, giving url variable necessary value
